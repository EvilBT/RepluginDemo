# 出现以下错误
FATAL EXCEPTION: main

Process: xyz.zpayh.replugindemo, PID: 21645
java.lang.RuntimeException: Unable to start activity ComponentInfo{xyz.zpayh.replugindemo/xyz.zpayh.replugindemo.loader.a.ActivityN1NRNTS4}: java.lang.ClassCastException: android.support.v7.widget.ActionBarOverlayLayout cannot be cast to android.support.v7.widget.DecorContentParent

    at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2650)
    at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2720)
    at android.app.ActivityThread.-wrap12(ActivityThread.java)
    at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1567)
    at android.os.Handler.dispatchMessage(Handler.java:111)
    at android.os.Looper.loop(Looper.java:207)
    at android.app.ActivityThread.main(ActivityThread.java:5917)
    at java.lang.reflect.Method.invoke(Native Method)
    at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:789)
    at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:679)

 Caused by: java.lang.ClassCastException: android.support.v7.widget.ActionBarOverlayLayout cannot be cast to android.support.v7.widget.DecorContentParent