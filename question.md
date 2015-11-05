Question
===
###Custom inputType / key set for Android soft keyboard

###AdapterView getView return null;
java.lang.NullPointerException: Attempt to invoke virtual method 'int android.view.View.getImportantForAccessibility()' on a null object reference
###Media Player
Media Player called in state 0, error (-38,0)
###android proguard onItemClick Unknown Source


###4.3线上内测
10-22 11:19:33.777 22706-22708/com.eduu.bang D/dalvikvm: GC_CONCURRENT freed 1637K, 8% free 27772K/30023K, paused 7ms+11ms, total 117ms
10-22 11:19:33.782 22706-22715/com.eduu.bang W/dalvikvm: No implementation found for native Lcom/tal/media/a/k;.y:()V
10-22 11:19:33.782 22706-22715/com.eduu.bang E/System: Uncaught exception thrown by finalizer
10-22 11:19:33.782 22706-22715/com.eduu.bang E/System: java.lang.UnsatisfiedLinkError: Native method not found: com.tal.media.a.k.y:()V
                                                           at com.tal.media.a.k.y(Native Method)
                                                           at com.tal.media.a.k.finalize(Unknown Source)
                                                           at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:186)
                                                           at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:169)
                                                           at java.lang.Thread.run(Thread.java:856)
10-22 11:19:33.947 22706-22706/com.eduu.bang E/AndroidRuntime: FATAL EXCEPTION: main
                                                               java.lang.UnsatisfiedLinkError: unknown failure
                                                                   at java.lang.Runtime.loadLibrary(Runtime.java:370)
                                                                   at java.lang.System.loadLibrary(System.java:535)
                                                                   at com.tal.media.a.j.a(Unknown Source)
                                                                   at com.tal.media.a.k.a(Unknown Source)
                                                                   at com.tal.media.a.k.<init>(Unknown Source)
                                                                   at com.tal.media.a.k.<init>(Unknown Source)
                                                                   at com.tal.media.widget.VideoView.m(Unknown Source)
                                                                   at com.tal.media.widget.VideoView.v(Unknown Source)
                                                                   at com.tal.media.widget.VideoView$2.surfaceCreated(Unknown Source)
                                                                   at android.view.SurfaceView.updateWindow(SurfaceView.java:609)
                                                                   at android.view.SurfaceView.access$000(SurfaceView.java:86)
                                                                   at android.view.SurfaceView$3.onPreDraw(SurfaceView.java:178)
                                                                   at android.view.ViewTreeObserver.dispatchOnPreDraw(ViewTreeObserver.java:707)
                                                                   at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1952)
                                                                   at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1118)
                                                                   at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:4525)
                                                                   at android.view.Choreographer$CallbackRecord.run(Choreographer.java:725)
                                                                   at android.view.Choreographer.doCallbacks(Choreographer.java:555)
                                                                   at android.view.Choreographer.doFrame(Choreographer.java:525)
                                                                   at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:711)
                                                                   at android.os.Handler.handleCallback(Handler.java:615)
                                                                   at android.os.Handler.dispatchMessage(Handler.java:92)
                                                                   at android.os.Looper.loop(Looper.java:137)
                                                                   at android.app.ActivityThread.main(ActivityThread.java:4946)
                                                                   at java.lang.reflect.Method.invokeNative(Native Method)
                                                                   at java.lang.reflect.Method.invoke(Method.java:511)
                                                                   at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1036)
                                                                   at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:803)
                                                                   at dalvik.system.NativeStart.main(Native Method)
10-22 11:19:35.857 22706-26490/com.eduu.bang I/Crashlytics: Crashlytics report upload complete: 562855810231-0001-58B2-819200611DF0.cls
10-22 11:20:45.632 22706-22708/com.eduu.bang D/dalvikvm: GC_CONCURRENT freed 1886K, 9% free 27867K/30343K, paused 11ms+8ms, total 107ms
10-22 11:21:09.502 22706-22713/com.eduu.bang I/dalvikvm: Jit: resizing JitTable from 8192 to 16384
10-22 11:21:09.522 22706-24659/com.eduu.bang D/b: (a:-1) : com.eduu.bang.chat.b.a@42e76660------XMPP packet received - sending Intent: com.eduu.bang.chat.service.action.XMPP.MESSAGE_RECEIVED data---><message to='游客1024@jzb.com/67394150963253' from='512902@groupchat.jzb.com/冰箱里有比目鱼' type='groupchat'><body>{&quot;id&quot;:&quot;8d8553a72ff649e98730df98494f1910&quot;,&quot;type&quot;:&quot;richSystem&quot;,&quot;content&quot;:&quot;未知消息类型，请升级最新版本&quot;,&quot;extcon&quot;:&quot;{\&quot;time\&quot;:1445484069}&quot;,&quot;name&quot;:&quot;冰箱里有比目鱼&quot;,&quot;nickname&quot;:&quot;&quot;,&quot;subType&quot;:&quot;endClass&quot;}</body><time xmlns="jabber:client">1445484069436</time></message>
10-22 11:21:09.527 22706-24659/com.eduu.bang D/b: (a:-1) : XMPP packet received - 实时消息 data===>{"id":"8d8553a72ff649e98730df98494f1910","type":"richSystem","content":"未知消息类型，请升级最新版本","extcon":"{\"time\":1445484069}","name":"冰箱里有比目鱼","nickname":"","subType":"endClass"}

###4.3打包
The same input jar [/Users/wiki/workspace/BangSVN/Bang/libs/alipaySDK-20150818.jar] is specified twice

-dontwarn
Note: there were 59 duplicate class definitions.
      (http://proguard.sourceforge.net/manual/troubleshooting.html#duplicateclass)
Warning: com.alipay.apmobilesecuritysdk.face.APSecuritySdk$RunningTask$1: can't find superclass or interface com.taobao.dp.client.IInitResultListener
Warning: com.alipay.apmobilesecuritysdk.face.APSecuritySdk: can't find referenced class com.taobao.dp.DeviceSecuritySDK
Warning: com.alipay.apmobilesecuritysdk.face.APSecuritySdk: can't find referenced class com.taobao.dp.DeviceSecuritySDK
Warning: com.alipay.apmobilesecuritysdk.face.APSecuritySdk: can't find referenced class com.taobao.dp.DeviceSecuritySDK
Warning: com.alipay.apmobilesecuritysdk.face.APSecuritySdk$RunningTask: can't find referenced class com.taobao.dp.DeviceSecuritySDK
Warning: com.alipay.apmobilesecuritysdk.face.APSecuritySdk$RunningTask: can't find referenced class com.taobao.dp.DeviceSecuritySDK
Warning: com.alipay.apmobilesecuritysdk.face.APSecuritySdk$RunningTask: can't find referenced class com.taobao.dp.DeviceSecuritySDK
Warning: com.alipay.apmobilesecuritysdk.face.APSecuritySdk$RunningTask: can't find referenced class com.taobao.dp.DeviceSecuritySDK
Warning: com.alipay.apmobilesecuritysdk.face.APSecuritySdk$RunningTask$1: can't find referenced class com.taobao.dp.client.IInitResultListener
Warning: there were 9 unresolved references to classes or interfaces.
         You may need to add missing library jars or update their versions.
         If your code works fine without the missing classes, you can suppress
         the warnings with '-dontwarn' options.
         (http://proguard.sourceforge.net/manual/troubleshooting.html#unresolvedclass)
Exception while processing task 
java.io.IOException: Please correct the above warnings first.
        at proguard.Initializer.execute(Initializer.java:473)
        at proguard.ProGuard.initialize(ProGuard.java:233)
        at proguard.ProGuard.execute(ProGuard.java:98)
        at proguard.gradle.ProGuardTask.proguard(ProGuardTask.java:1074)
        at com.android.build.gradle.tasks.AndroidProGuardTask.doMinification(AndroidProGuardTask.java:139)
        at com.android.build.gradle.tasks.AndroidProGuardTask$1.run(AndroidProGuardTask.java:115)
        at com.android.builder.tasks.Job.runTask(Job.java:48)
        at com.android.build.gradle.tasks.SimpleWorkQueue$EmptyThreadContext.runTask(SimpleWorkQueue.java:41)
        at com.android.builder.tasks.WorkQueue.run(WorkQueue.java:227)
        at java.lang.Thread.run(Thread.java:745)
:Bang:shrinkWebsiteReleaseMultiDexComponents FAILED

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':Bang:shrinkWebsiteReleaseMultiDexComponents'.
> java.io.IOException: The output jar [/Users/wiki/workspace/BangSVN/Bang/build/intermediates/multi-dex/website/release/componentClasses.jar] must be specified after an input jar, or it will be empty.

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

BUILD FAILED

Total time: 4 mins 0.759 secs

###音频切换
Android中音频通道路径切换
###orientation change
android screen orientation change
###Parcelable
this class implements parcelable but does not provide a creator field

###Caused by: java.lang.NullPointerException
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.support.v4.app.BackStackRecord.run(BackStackRecord.java:709)

10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime: FATAL EXCEPTION: main
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime: java.lang.RuntimeException: Unable to resume activity {com.eduu.bang/com.eduu.bang.chat.ChatActivity}: java.lang.NullPointerException
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.performResumeActivity(ActivityThread.java:2642)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:2670)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1279)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.os.Handler.dispatchMessage(Handler.java:99)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.os.Looper.loop(Looper.java:137)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.main(ActivityThread.java:4946)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at java.lang.reflect.Method.invokeNative(Native Method)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at java.lang.reflect.Method.invoke(Method.java:511)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1036)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:803)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at dalvik.system.NativeStart.main(Native Method)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:  Caused by: java.lang.NullPointerException
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.support.v4.app.BackStackRecord.run(BackStackRecord.java:709)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.support.v4.app.FragmentManagerImpl.execPendingActions(FragmentManager.java:1501)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.support.v4.app.FragmentActivity.onResume(FragmentActivity.java:426)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at com.pobear.BaseActivity.onResume(BaseActivity.java:108)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at com.eduu.bang.chat.ChatActivity.onResume(ChatActivity.java:107)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1199)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.Activity.performResume(Activity.java:5280)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.performResumeActivity(ActivityThread.java:2632)
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:2670) 
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1279) 
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.os.Handler.dispatchMessage(Handler.java:99) 
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.os.Looper.loop(Looper.java:137) 
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.main(ActivityThread.java:4946) 
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at java.lang.reflect.Method.invokeNative(Native Method) 
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at java.lang.reflect.Method.invoke(Method.java:511) 
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1036) 
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:803) 
10-12 13:53:51.875 6607-6607/com.eduu.bang E/AndroidRuntime:     at dalvik.system.NativeStart.main(Native Method) 

###Duplicate id 0x7f0c0188, tag null, or parent id 0x0 with another fragment for com.eduu.bang.emoji.EmojiconsFragment
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime: FATAL EXCEPTION: main
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime: android.view.InflateException: Binary XML file line #126: Error inflating class fragment
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:704)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:746)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:749)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:749)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.parseInclude(LayoutInflater.java:830)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:736)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:749)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.inflate(LayoutInflater.java:489)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.inflate(LayoutInflater.java:396)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.inflate(LayoutInflater.java:352)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.View.inflate(View.java:16428)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at com.eduu.bang.component.ChatComponent$ChatPresenterImpl.onNewIntent(ChatComponent.java:415)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at com.eduu.bang.chat.ChatActivity.onNewIntent(ChatActivity.java:543)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.Instrumentation.callActivityOnNewIntent(Instrumentation.java:1168)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.deliverNewIntents(ActivityThread.java:2203)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.performNewIntents(ActivityThread.java:2216)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.handleNewIntent(ActivityThread.java:2225)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.access$1500(ActivityThread.java:140)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1308)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.os.Handler.dispatchMessage(Handler.java:99)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.os.Looper.loop(Looper.java:137)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.main(ActivityThread.java:4946)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at java.lang.reflect.Method.invokeNative(Native Method)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at java.lang.reflect.Method.invoke(Method.java:511)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1036)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:803)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at dalvik.system.NativeStart.main(Native Method)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:  Caused by: java.lang.IllegalArgumentException: Binary XML file line #126: Duplicate id 0x7f0c0188, tag null, or parent id 0x0 with another fragment for com.eduu.bang.emoji.EmojiconsFragment
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.support.v4.app.FragmentManagerImpl.onCreateView(FragmentManager.java:2175)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.support.v4.app.FragmentActivity.onCreateView(FragmentActivity.java:300)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:676)
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:746) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:749) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:749) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.parseInclude(LayoutInflater.java:830) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:736) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.rInflate(LayoutInflater.java:749) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.inflate(LayoutInflater.java:489) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.inflate(LayoutInflater.java:396) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.LayoutInflater.inflate(LayoutInflater.java:352) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.view.View.inflate(View.java:16428) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at com.eduu.bang.component.ChatComponent$ChatPresenterImpl.onNewIntent(ChatComponent.java:415) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at com.eduu.bang.chat.ChatActivity.onNewIntent(ChatActivity.java:543) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.Instrumentation.callActivityOnNewIntent(Instrumentation.java:1168) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.deliverNewIntents(ActivityThread.java:2203) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.performNewIntents(ActivityThread.java:2216) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.handleNewIntent(ActivityThread.java:2225) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.access$1500(ActivityThread.java:140) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1308) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.os.Handler.dispatchMessage(Handler.java:99) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.os.Looper.loop(Looper.java:137) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at android.app.ActivityThread.main(ActivityThread.java:4946) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at java.lang.reflect.Method.invokeNative(Native Method) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at java.lang.reflect.Method.invoke(Method.java:511) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1036) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:803) 
10-12 13:10:40.220 11513-11513/com.eduu.bang E/AndroidRuntime:     at dalvik.system.NativeStart.main(Native Method) 
###retrofit

retrofit call execute android.os.StrictMode$AndroidBlockGuardPolicy.onNetwork

okhttp

###UI控件库
Android UI库
https://github.com/wasabeef/awesome-android-ui

IOS UI库
https://github.com/cjwirth/awesome-ios-ui

###asmack android
SmackAndroid Failed to initialize resolver org xbill DNS Lookup refreshDefault

SmackAndroid ExceptionInInitializerError SmackAndroid.java 42


09-14 10:31:21.970 22938-22972/com.eduu.bang E/AndroidRuntime: FATAL EXCEPTION: Thread-705
09-14 10:31:21.970 22938-22972/com.eduu.bang E/AndroidRuntime: java.lang.ExceptionInInitializerError
09-14 10:31:21.970 22938-22972/com.eduu.bang E/AndroidRuntime:     at org.jivesoftware.smack.SmackAndroid$1$1.run(SmackAndroid.java:42)
09-14 10:31:21.970 22938-22972/com.eduu.bang E/AndroidRuntime:  Caused by: java.lang.RuntimeException: Failed to initialize resolver
09-14 10:31:21.970 22938-22972/com.eduu.bang E/AndroidRuntime:     at org.xbill.DNS.Lookup.refreshDefault(Lookup.java:89)
09-14 10:31:21.970 22938-22972/com.eduu.bang E/AndroidRuntime:     at org.xbill.DNS.Lookup.<clinit>(Lookup.java:97)
09-14 10:31:21.970 22938-22972/com.eduu.bang E/AndroidRuntime:     at org.jivesoftware.smack.SmackAndroid$1$1.run(SmackAndroid.java:42) 
###6.Android studio 打包错误
gradle Error duplicate files during packaging commons-io  httpmime jar

Error: duplicate files during packaging of APK /Users/wiki/workspace/BangProject/Bang/build/outputs/apk/Bang-website-debug-unaligned.apk
	Path in archive: META-INF/NOTICE.txt
	Origin 1: /Users/wiki/develop/gradle/gradle-2.5/caches/modules-2/files-2.1/commons-io/commons-io/2.4/b1b6ea3b7e4aa4f492509a4952029cd8e48019ad/commons-io-2.4.jar
	Origin 2: /Users/wiki/workspace/BangProject/Bang/libs/httpmime-4.1.3.jar
You can ignore those files in your build.gradle:
	android {
	  packagingOptions {
	    exclude 'META-INF/NOTICE.txt'
	  }
	}


###5.引入square的OkHttp Retrofit引起的混淆问题
java.io.IOException: Can't write [/Users/wiki/workspace/BangProject/Bang/build/intermediates/classes-proguard/website/debug/classes.jar] (Can't read [/Users/wiki/workspace/BangProject/Bang/build/intermediates/exploded-aar/BangProject/Android-Pobear/unspecified/jars/libs/gson-2.3.1.jar(;;;;;;!META-INF/MANIFEST.MF)] (Duplicate zip entry [gson-2.3.1.jar:com/google/gson/annotations/Expose.class]))

java.io.IOException: Can't write build/intermediates/classes-proguard debug classes.jar

(Can't read [/Users/wiki/workspace/BangProject/Bang/build/intermediates/exploded-aar/BangProject/Android-Pobear/unspecified/jars/libs/gson-2.3.1.jar(;;;;;;!META-INF/MANIFEST.MF)] (Duplicate zip entry [gson-2.3.1.jar:com/google/gson/annotations/Expose.class]))

###4.How to disable copy/paste from/to EditText

###3.edittext-clear-focus-on-touch-outside
[点击其他地方，去除edittext焦点](http://stackoverflow.com/questions/4828636/edittext-clear-focus-on-touch-outside)

I tried all these solutions. edc598's was the closest to working, but touch events did not trigger on other Views contained in the layout. In case anyone needs this behavior, this is what I ended up doing:

I created an (invisible) FrameLayout called touchInterceptor as the last View in the layout so that it overlays everything (edit: you also have to use a RelativeLayout as the parent layout and give the touchInterceptor fill_parent attributes). Then I used it to intercept touches and determine if the touch was on top of the EditText or not:

FrameLayout touchInterceptor = (FrameLayout)findViewById(R.id.touchInterceptor);
touchInterceptor.setOnTouchListener(new OnTouchListener() {
    @Override
    public boolean onTouch(View v, MotionEvent event) {
        if (event.getAction() == MotionEvent.ACTION_DOWN) {
            if (mEditText.isFocused()) {
                Rect outRect = new Rect();
                mEditText.getGlobalVisibleRect(outRect);
                if (!outRect.contains((int)event.getRawX(), (int)event.getRawY())) {
                    mEditText.clearFocus();
                    InputMethodManager imm = (InputMethodManager) v.getContext().getSystemService(Context.INPUT_METHOD_SERVICE); 
                    imm.hideSoftInputFromWindow(v.getWindowToken(), 0);
                }
            }
        }
        return false;
    }
});
Return false to let the touch handling fall through.

It's hacky, but it's the only thing that worked for me.

###2.Stop EditText from gaining focus at Activity startup

[进入界面，禁止Edittext 自动获取焦点](http://stackoverflow.com/questions/1555109/stop-edittext-from-gaining-focus-at-activity-startup)

###1.Obfuscating Android Applications using O-LLVM and the NDK
混淆处理Android中的字符串




###1.在听筒播放语音
[Android - Play audio from earpiece](http://stackoverflow.com/questions/13960313/android-play-audio-from-earpiece)

###2.粘贴 保留 网页
[如何复制网页内容但粘贴网页代码？ - 知乎](http://www.zhihu.com/question/20401989)

###3.[Caching Bitmaps](http://developer.android.com/training/displaying-bitmaps/cache-bitmap.html)

###4.[How to scale images for your Android™ application](http://developer.sonymobile.com/2011/06/27/how-to-scale-images-for-your-android-application/)

###5.[Android: high quality image resizing / scaling](http://stackoverflow.com/questions/4207562/android-high-quality-image-resizing-scaling)

###6.[Android set View.GONE does not “release” space in listview](http://stackoverflow.com/questions/7917049/android-set-view-gone-does-not-release-space-in-listview)

[于是我和他说 只要按照我的学 半年内可以学会 按照这样的流程
《C++ 程序设计》（c++基础） 《windows程序设计》（看几遍能懂就行）《深入浅出MFC》（VC基础）《windows核心编程》（了解windows系统初级读物） 看完这几本书就可以开始做外挂了
如果还想学破解 也不需要看其他书 把汇编语言学会 工具 OLLYDBG IDA会用 就OK 了](http://www.jiluzhe.net/archives/50)


###6.[android webview keyboard hides input field]()

###7.[keyboard-hiding-edittext-when-androidwindowtranslucentstatus-true](http://stackoverflow.com/questions/19897422/keyboard-hiding-edittext-when-androidwindowtranslucentstatus-true)

###8.Soft Keyboard Covers Form Fields on Android 

###9.[Parsing Data for android-21 failed Unsupported major.minor version 51.0](http://code2care.org/pages/android-parsing-data-for-android-l-failed-unsupported-major.minor-version-51.0-error/)

###10.http://stackoverflow.com/questions/26474298/android-parsing-data-for-android-21-failed


###[11.Android-ActionItemBadge](https://github.com/mikepenz/Android-ActionItemBadge)

ActionItemBadge is a library which offers a simple and easy to use method to add a badge to your action item!

[Is there a way to add a badge to an application icon in Android?](http://stackoverflow.com/questions/2905542/is-there-a-way-to-add-a-badge-to-an-application-icon-in-android/20213081#20213081)

[How to display count of notifications in app launcher icon](http://stackoverflow.com/questions/17565307/how-to-display-count-of-notifications-in-app-launcher-icon/24804467#24804467)

[ShortcutBadger](https://github.com/leolin310148/ShortcutBadger)

###12 [how-to-override-android-back-key-when-soft-keyboard-is-open/](https://emumair.wordpress.com/2011/11/22/how-to-override-android-back-key-when-soft-keyboard-is-open/)

[Android back key event - while displaying soft keyboard](http://www.acnenomor.com/4676689p1/android-back-key-event-while-displaying-soft-keyboard)

[android back key event while displaying soft keyboard](http://www.acnenomor.com/3586562p2/android-back-key-event-while-displaying-soft-keyboard)

###13[NullPointerException at TextView.checkForRelayout() while setText()](http://stackoverflow.com/questions/16281357/nullpointerexception-at-textview-checkforrelayout-while-settext)

###14.[android custom url scheme](http://stackoverflow.com/questions/4023273/android-custom-url-scheme)

[java.lang.IllegalArgumentException: pointerIndex out of range](https://github.com/chrisbanes/PhotoView/issues/206)

###15.[android ScrollView not show top]()
android scrollview 不在顶部
###16.[Check if the broadcstreceiver is registered?](http://stackoverflow.com/questions/20329949/check-if-the-broadcstreceiver-is-registered)
[how to check if Receiver is registered in android](http://stackoverflow.com/questions/2682043/how-to-check-if-receiver-is-registered-in-android)

###17.[How to solve Runtime error in Android bin res crunch directory?](http://stackoverflow.com/questions/20923251/how-to-solve-runtime-error-in-android-bin-res-crunch-directory)

###18.[ListView with large images and memory management (android mostly)](https://developer.appcelerator.com/question/164093/listview-with-large-images-and-memory-management-android-mostly)

[Many and Large image loading in Android](http://stackoverflow.com/questions/11040255/many-and-large-image-loading-in-android)

###19[Installation error INSTALL_FAILED_DEXOPT]()

###20[List View smoothScrollToPosition is not scrolling to expected position](http://stackoverflow.com/questions/26376139/list-view-smoothscrolltoposition-is-not-scrolling-to-expected-position)

###21[LinearAlloc exceeded capacity (5242880)]()
###22[android UnsupportedOperationException NoSuchMethodException]()

###23[Activity has leaked ServiceConnection that was originally bound here]()

###24[Android Device Chooser — device not showing up](http://stackoverflow.com/questions/2256884/android-device-chooser-device-not-showing-up)

###25网易轻松一刻[Which is better for loading large size images in Android, Image View or Web View?](http://www.quora.com/Which-is-better-for-loading-large-size-images-in-Android-Image-View-or-Web-View)

###26.[How can I create a rectangle with two curved sides in XML drawable?](http://stackoverflow.com/questions/18071216/how-can-i-create-a-rectangle-with-two-curved-sides-in-xml-drawable)

![image](http://i.stack.imgur.com/xKazZ.gif)

###27.[android game develop tutorial]()Android 游戏开发
[Android Game Development Tutorial! (Beginners welcome).](http://forum.xda-developers.com/showthread.php?p=28323110#post28323110)

###28.[How to deserialize a LIST using GSON or another JSON to Java?](http://stackoverflow.com/questions/4318458/how-to-deserialize-a-list-using-gson-or-another-json-to-java)

###29[onactivityresult called immediately after startactivityforresult](http://stackoverflow.com/questions/7910840/android-startactivityforresult-immediately-triggering-onactivityresult)

###30.[android add parameter to url](http://stackoverflow.com/questions/19167954/use-uri-builder-in-android-or-create-url-with-variables#)

Let's say that I want to create the following URL:

https://www.myawesomesite.com/turtles/types?type=1&sort=relevance#section-name
To build this with the Uri.Builder I would do the following.

Uri.Builder builder = new Uri.Builder();
builder.scheme("https")
    .authority("www.myawesomesite.com")
    .appendPath("turtles")
    .appendPath("types")
    .appendQueryParameter("type", "1")
    .appendQueryParameter("sort", "relevance")
    .fragment("section-name");
String myUrl = builder.build().toString();


###31[Set ListView item height](http://stackoverflow.com/questions/9439401/set-listview-item-height)

How are you inflating the view?

If you are setting 'parent' parameter to null like below, then layout parameters are ignored.

@Override
public View getView(int position, View convertView, ViewGroup parent) {
  ...
  View v = inflater.inflate(R.layout.filtered_trip_row, null);
  …

  return v;
}
Passing 'parent' to inflate should work as you expect.

@Override
public View getView(int position, View convertView, ViewGroup parent) {
  ...
  View v = inflater.inflate(R.layout.filtered_trip_row, parent);
  …

  return v;
}
This explains it in detail: Making sense of LayoutInflater

###32[How to assign padding to Listview item divider line](http://stackoverflow.com/questions/14054364/how-to-assign-padding-to-listview-item-divider-line)

Use 'inset'.....

(list_divider.xml)

<?xml version="1.0" encoding="UTF-8"?>
<inset xmlns:android="http://schemas.android.com/apk/res/android"
    android:insetLeft="50dp"
    android:insetRight="50dp" >

 <shape>
    <solid android:color="@color/orange" />
    <corners android:radius="2.0dip" />
</shape>

</inset>
and in your list view add like this...

<ListView
    android:dividerHeight="2dp"
    android:divider="@drawable/list_divider"
    ...
/>
you can set the inset value as desired...

###33[How to generate Class Diagram (UML) on android studio](http://stackoverflow.com/questions/17123384/how-to-generate-class-diagram-uml-on-android-studio)


###34发送Emoji表情到服务器 [Post UTF-8 encoded data to server loses certain characters](http://stackoverflow.com/questions/5270591/post-utf-8-encoded-data-to-server-loses-certain-characters)

0 = '\uD83D' 55357
1 = '\uDE0D' 56845

111111😍222222

1\uD83D\uDE0D2

###35[android studio Waiting until last debugger command completes]()
Android Studio 1.2 beta version hangs on debugging
Debugging with Android Studio stuck at “Waiting For Debugger” forever

###37[How to Add Stacktrace or debug Option when Building Android Studio Project](http://stackoverflow.com/questions/21674091/how-to-add-stacktrace-or-debug-option-when-building-android-studio-project)

:myapp:processDebugResources FAILED

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':olevelphysics:processDebugResources'.
...
...

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.


###38.[android-maven-plugin 3.6.1 generate-sources NoClassDefFoundError RepositorySystem]()

android maven plugin 3.6.1 NoClassDefFoundError RepositorySystem

android-maven-plugin:3.6.1: 

generate-sources (default-generate-sources) @ android-sample ---
[WARNING] Error injecting: com.jayway.maven.plugins.android.phase01generatesources.GenerateSourcesMojo
java.lang.NoClassDefFoundError: Lorg/sonatype/aether/RepositorySystem;
        at java.lang.Class.getDeclaredFields0(Native Method)
        at java.lang.Class.privateGetDeclaredFields(Class.java:2575)
        at java.lang.Class.getDeclaredFields(Class.java:1908)
        at com.google.inject.spi.InjectionPoint.getInjectionPoints(InjectionPoint.java:661)
        at com.google.inject.spi.InjectionPoint.forInstanceMethodsAndFields(InjectionPoint.java:366)
        at com.google.inject.internal.ConstructorBindingImpl.getInternalDependencies(ConstructorBindingImpl.java:165)
        at com.google.inject.internal.InjectorImpl.getInternalDependencies(InjectorImpl.java:612)
        at com.google.inject.internal.InjectorImpl.cleanup(InjectorImpl.java:568)
        at com.google.inject.internal.InjectorImpl.initializeJitBinding(InjectorImpl.java:554)
        at com.google.inject.internal.InjectorImpl.createJustInTimeBinding(InjectorImpl.java:877)
        at com.google.inject.internal.InjectorImpl.createJustInTimeBindingRecursive(InjectorImpl.java:798)
        at com.google.inject.internal.InjectorImpl.getJustInTimeBinding(InjectorImpl.java:281)
        at com.google.inject.internal.InjectorImpl.getBindingOrThrow(InjectorImpl.java:213)
        at com.google.inject.internal.InjectorImpl.getProviderOrThrow(InjectorImpl.java:998)
        at com.google.inject.internal.InjectorImpl.getProvider(InjectorImpl.java:1031)
        at com.google.inject.internal.InjectorImpl.getProvider(InjectorImpl.java:994)
        at com.google.inject.internal.InjectorImpl.getInstance(InjectorImpl.java:1044)
        at org.eclipse.sisu.space.AbstractDeferredClass.get(AbstractDeferredClass.java:48)
        at com.google.inject.internal.ProviderInternalFactory.provision(ProviderInternalFactory.java:86)
        at com.google.inject.internal.InternalFactoryToInitializableAdapter.provision(InternalFactoryToInitializableAdapter.java:54)
        at com.google.inject.internal.ProviderInternalFactory$1.call(ProviderInternalFactory.java:70)
        at com.google.inject.internal.ProvisionListenerStackCallback$Provision.provision(ProvisionListenerStackCallback.java:115)
        at org.eclipse.sisu.bean.BeanScheduler$Activator.onProvision(BeanScheduler.java:176)
        at com.google.inject.internal.ProvisionListenerStackCallback$Provision.provision(ProvisionListenerStackCallback.java:126)
        at com.google.inject.internal.ProvisionListenerStackCallback.provision(ProvisionListenerStackCallback.java:68)
        at com.google.inject.internal.ProviderInternalFactory.circularGet(ProviderInternalFactory.java:68)
        at com.google.inject.internal.InternalFactoryToInitializableAdapter.get(InternalFactoryToInitializableAdapter.java:46)
        at com.google.inject.internal.InjectorImpl$2$1.call(InjectorImpl.java:1009)
        at com.google.inject.internal.InjectorImpl.callInContext(InjectorImpl.java:1059)
        at com.google.inject.internal.InjectorImpl$2.get(InjectorImpl.java:1005)
        at com.google.inject.internal.SingletonScope$1.get(SingletonScope.java:36)
        at org.eclipse.sisu.inject.LazyBeanEntry.getValue(LazyBeanEntry.java:81)
        at org.eclipse.sisu.plexus.LazyPlexusBean.getValue(LazyPlexusBean.java:51)
        at org.codehaus.plexus.DefaultPlexusContainer.lookup(DefaultPlexusContainer.java:263)
        at org.codehaus.plexus.DefaultPlexusContainer.lookup(DefaultPlexusContainer.java:255)
        at org.apache.maven.plugin.internal.DefaultMavenPluginManager.getConfiguredMojo(DefaultMavenPluginManager.java:543)
        at org.apache.maven.plugin.DefaultBuildPluginManager.executeMojo(DefaultBuildPluginManager.java:121)
        at org.apache.maven.lifecycle.internal.MojoExecutor.execute(MojoExecutor.java:208)
        at org.apache.maven.lifecycle.internal.MojoExecutor.execute(MojoExecutor.java:153)
        at org.apache.maven.lifecycle.internal.MojoExecutor.execute(MojoExecutor.java:145)
        at org.apache.maven.lifecycle.internal.LifecycleModuleBuilder.buildProject(LifecycleModuleBuilder.java:116)
        at org.apache.maven.lifecycle.internal.LifecycleModuleBuilder.buildProject(LifecycleModuleBuilder.java:80)
        at org.apache.maven.lifecycle.internal.builder.singlethreaded.SingleThreadedBuilder.build(SingleThreadedBuilder.java:51)
        at org.apache.maven.lifecycle.internal.LifecycleStarter.execute(LifecycleStarter.java:128)
        at org.apache.maven.DefaultMaven.doExecute(DefaultMaven.java:307)
        at org.apache.maven.DefaultMaven.doExecute(DefaultMaven.java:193)
        at org.apache.maven.DefaultMaven.execute(DefaultMaven.java:106)
        at org.apache.maven.cli.MavenCli.execute(MavenCli.java:862)
        at org.apache.maven.cli.MavenCli.doMain(MavenCli.java:286)
        at org.apache.maven.cli.MavenCli.main(MavenCli.java:197)
        at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
        at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
        at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
        at java.lang.reflect.Method.invoke(Method.java:483)
        at org.codehaus.plexus.classworlds.launcher.Launcher.launchEnhanced(Launcher.java:289)
        at org.codehaus.plexus.classworlds.launcher.Launcher.launch(Launcher.java:229)
        at org.codehaus.plexus.classworlds.launcher.Launcher.mainWithExitCode(Launcher.java:415)
        at org.codehaus.plexus.classworlds.launcher.Launcher.main(Launcher.java:356)
Caused by: java.lang.ClassNotFoundException: org.sonatype.aether.RepositorySystem
        at org.codehaus.plexus.classworlds.strategy.SelfFirstStrategy.loadClass(SelfFirstStrategy.java:50)
        at org.codehaus.plexus.classworlds.realm.ClassRealm.unsynchronizedLoadClass(ClassRealm.java:271)
        at org.codehaus.plexus.classworlds.realm.ClassRealm.loadClass(ClassRealm.java:247)
        at org.codehaus.plexus.classworlds.realm.ClassRealm.loadClass(ClassRealm.java:239)
        ... 58 more
        
###39.java.lang.ClassCastException: org.apache.maven.shared.dependency.graph.internal.Maven31DependencyGraphBuilder cannot be cast to org.apache.maven.shared.dependency.graph.DependencyGraphBuilder    


ClassCastException Maven31DependencyGraphBuilder cannot be cast to DependencyGraphBuilder 


android-maven-plugin:3.6.1:generate-sources (default-generate-sources) @ android-sample ---
[WARNING] Error injecting: com.jayway.maven.plugins.android.phase01generatesources.GenerateSourcesMojo
java.lang.NoClassDefFoundError: Lorg/sonatype/aether/RepositorySystem;

android-maven-plugin:3.6.1:generate-sources NoClassDefFoundError org/sonatype/aether/RepositorySystem;

<plugin>
  <groupId>com.simpligility.maven.plugins</groupId>
  <artifactId>android-maven-plugin</artifactId>
  <version>4.2.0</version>
  <extensions>true</extensions>
</plugin>


###40.[Android classes not found during sonar anaysis](http://stackoverflow.com/questions/24907810/android-classes-not-found-during-sonar-anaysis)


###41.[Avoid memory leaks on Android](http://www.curious-creature.com/2008/12/18/avoid-memory-leaks-on-android/comment-page-1/)

###42.[Unable to execute dex: GC overhead limit exceeded GC overhead limit exceeded](http://jingyan.baidu.com/article/0a52e3f419f60dbf62ed7212.html)

[2015-05-26 16:40:27 - Dex Loader] Unable to execute dex: Cannot merge new index 66968 into a non-jumbo instruction!
[2015-05-26 16:40:27 - scriptelf_core] Conversion to Dalvik format failed: Unable to execute dex: Cannot merge new index 66968 into a non-jumbo instruction!


###43.android url scheme open app

###44.java 正则表达式 匹配 嵌套标签

###45.git 

[Difference between “git add -A” and “git add .”](http://stackoverflow.com/questions/572549/difference-between-git-add-a-and-git-add#)

git add -A stages All
git add . stages new and modified, without deleted
git add -u stages modified and deleted, without new

###46.document-getelementbyid-value-return-undefined-in-chrome

chrome-firefox-console-log-always-prepends-a-line-saying-undefined

###47.call-a-function-after-complete-page-load
###48.javascript a click override
###49.Check if application is installed - Android
How to check whether an application is installed in your ANDROID Phone?

###50.Android DialogFragment vs Dialog


06-11 13:53:42.854    5493-5493/com.scriptelf E/AndroidRuntime﹕ FATAL EXCEPTION: main
    java.lang.UnsatisfiedLinkError: Couldn't load scriptelf: findLibrary returned null
            at java.lang.Runtime.loadLibrary(Runtime.java:365)
            at java.lang.System.loadLibrary(System.java:535)
            at com.scriptelf.core.SEManager.init(SEManager.java:251)
            at com.scriptelf.tool.InitUtil.initScriptElf(InitUtil.java:41)
            at com.scriptelf.ui.MainActivity$2.handleMessage(MainActivity.java:161)
            at android.os.Handler.dispatchMessage(Handler.java:99)
            at android.os.Looper.loop(Looper.java:137)
            at android.app.ActivityThread.main(ActivityThread.java:4946)
            at java.lang.reflect.Method.invokeNative(Native Method)
            at java.lang.reflect.Method.invoke(Method.java:511)
            at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1036)
            at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:803)
            at dalvik.system.NativeStart.main(Native Method)
            
            
            
            06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ java.io.FileNotFoundException: 1.lua
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at android.content.res.AssetManager.openAsset(Native Method)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at android.content.res.AssetManager.open(AssetManager.java:315)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at android.content.res.AssetManager.open(AssetManager.java:289)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at com.scriptelf.core.SEManager.copyExec(SEManager.java:79)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at com.scriptelf.core.SEManager.copyExampleScript(SEManager.java:439)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at com.scriptelf.core.SEManager.init(SEManager.java:260)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at com.scriptelf.tool.InitUtil.initScriptElf(InitUtil.java:41)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at com.scriptelf.ui.MainActivity$2.handleMessage(MainActivity.java:161)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at android.os.Handler.dispatchMessage(Handler.java:99)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at android.os.Looper.loop(Looper.java:137)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at android.app.ActivityThread.main(ActivityThread.java:4946)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at java.lang.reflect.Method.invokeNative(Native Method)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at java.lang.reflect.Method.invoke(Method.java:511)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1036)
06-11 15:36:54.469    9657-9657/com.scriptelf W/System.err﹕ at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:803)
06-11 15:36:54.474    9657-9657/com.scriptelf W/System.err﹕ at dalvik.system.NativeStart.main(Native Method)
06-11 15:36:54.514    9657-9758/com.scriptelf W/System.err﹕ java.io.FileNotFoundException: /data/data/com.scriptelf/files/scriptelf/core/service/deamon/proc/main: open failed: ENOENT (No such file or directory)
06-11 15:36:54.514    9657-9758/com.scriptelf W/System.err﹕ at libcore.io.IoBridge.open(IoBridge.java:416)
06-11 15:36:54.514    9657-9758/com.scriptelf W/System.err﹕ at java.io.FileInputStream.<init>(FileInputStream.java:78)
06-11 15:36:54.519    9657-9758/com.scriptelf W/System.err﹕ at com.common.base.IO.readString(IO.java:40)
06-11 15:36:54.519    9657-9758/com.scriptelf W/System.err﹕ at com.common.base.IO.readString(IO.java:36)
06-11 15:36:54.519    9657-9758/com.scriptelf W/System.err﹕ at com.scriptelf.tool.root.RootUtil.isDeamonRunning(RootUtil.java:57)
06-11 15:36:54.519    9657-9758/com.scriptelf W/System.err﹕ at com.scriptelf.tool.root.RootUtil.startDeamon(RootUtil.java:81)
06-11 15:36:54.519    9657-9758/com.scriptelf W/System.err﹕ at com.scriptelf.core.SEManager.startDeamon(SEManager.java:168)
06-11 15:36:54.519    9657-9758/com.scriptelf W/System.err﹕ at com.scriptelf.core.SEManager$1.run(SEManager.java:293)
06-11 15:36:54.519    9657-9758/com.scriptelf W/System.err﹕ at java.lang.Thread.run(Thread.java:856)
06-11 15:36:54.519    9657-9758/com.scriptelf W/System.err﹕ Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
06-11 15:36:54.519    9657-9758/com.scriptelf W/System.err﹕ at libcore.io.Posix.open(Native Method)
06-11 15:36:54.524    9657-9758/com.scriptelf W/System.err﹕ at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
06-11 15:36:54.524    9657-9758/com.scriptelf W/System.err﹕ at libcore.io.IoBridge.open(IoBridge.java:400)
06-11 15:36:54.524    9657-9758/com.scriptelf W/System.err﹕ ... 8 more

###51.android develop pattern
android mvvm mvp

###52.Multiple annotations found at this line:
	- maven-enforcer-plugin (goal "enforce") is ignored by m2e.
	- Plugin execution not covered by lifecycle configuration: org.apache.maven.plugins:maven-checkstyle-plugin:2.10:checkstyle (execution: default, 
	 phase: compile)
	 
###53.[Prevent WebView from displaying “web page not available”](http://stackoverflow.com/questions/6552160/prevent-webview-from-displaying-web-page-not-available)

Handle network issues in webview

###54 [ListView insert data maintain(retain) view]()
[Adding new items to the beginning of listview, and maintaining the scroll position]()
插入数据后保持视图

The content of the adapter has changed but ListView did not receive a notification.

凡哥哥哥哥 1438845601681
痛快淋漓 1438854887874

1438854898029