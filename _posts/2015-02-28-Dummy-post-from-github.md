---
layout: post
title:  "Crashlytics issue"
date:   2015-02-28 11:06:00
categories: crashlytics
---
## New issue fired by `Crashlytics` on 27/2/15 

[Issue On ListAdapter Click][1]

It's showing following error

{% highlight java %}

Caused by java.lang.NullPointerException
com.cagy.androtv.adapters.ListChannel_Adapter.getCount (ListChannel_Adapter.java:46)
android.widget.ListView.setAdapter (ListView.java:486)
com.cagy.androtv.Video_Player_Fragment.onCreateView (Video_Player_Fragment.java:127)
android.support.v4.app.Fragment.performCreateView (Fragment.java:1786)
android.support.v4.app.FragmentManagerImpl.moveToState (FragmentManager.java:947)
android.support.v4.app.FragmentManagerImpl.moveToState (FragmentManager.java:1126)
android.support.v4.app.FragmentManagerImpl.moveToState (FragmentManager.java:1108)
android.support.v4.app.FragmentManagerImpl.dispatchActivityCreated (FragmentManager.java:1917)
android.support.v4.app.FragmentActivity.onStart (FragmentActivity.java:544)
android.app.Instrumentation.callActivityOnStart (Instrumentation.java:1177)
android.app.Activity.performStart (Activity.java:5461)
android.app.ActivityThread.performLaunchActivity (ActivityThread.java:2386)
android.app.ActivityThread.handleLaunchActivity (ActivityThread.java:2471)
android.app.ActivityThread.access$900 (ActivityThread.java:175)
android.app.ActivityThread$H.handleMessage (ActivityThread.java:1308)
android.os.Looper.loop (Looper.java:146)
android.app.ActivityThread.main (ActivityThread.java:5602)
java.lang.reflect.Method.invokeNative (Method.java)
dalvik.system.NativeStart.main (NativeStart.java)

{% endhighlight %}

[1]: https://fabric.io/blackid/android/apps/com.cagy.androtv/issues/54f090c67d7854d7c9933bf8
