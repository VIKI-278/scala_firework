error id: okPsDn4gc221OI7LmSjgUw==
### Bloop error:

Unexpected error when copying <WORKSPACE>\.bloop\fireworks\bloop-internal-classes\classes-Metals-B3OluLNpQ0GTp_kC65ZgiQ==-S4HIHANQTSyLqr0bzk3pDQ==\fireworks\Exploding.class to <WORKSPACE>\.bloop\fireworks\bloop-bsp-clients-classes\classes-Metals-B3OluLNpQ0GTp_kC65ZgiQ==\fireworks\Exploding.class, you might need to restart the build server.
java.nio.file.NoSuchFileException: <WORKSPACE>\.bloop\fireworks\bloop-internal-classes\classes-Metals-B3OluLNpQ0GTp_kC65ZgiQ==-S4HIHANQTSyLqr0bzk3pDQ==\fireworks\Exploding.class
	at java.base/sun.nio.fs.WindowsException.translateToIOException(WindowsException.java:85)
	at java.base/sun.nio.fs.WindowsException.rethrowAsIOException(WindowsException.java:103)
	at java.base/sun.nio.fs.WindowsException.rethrowAsIOException(WindowsException.java:108)
	at java.base/sun.nio.fs.WindowsFileCopy.copy(WindowsFileCopy.java:108)
	at java.base/sun.nio.fs.WindowsFileSystemProvider.copy(WindowsFileSystemProvider.java:282)
	at java.base/java.nio.file.Files.copy(Files.java:1304)
	at bloop.io.ParallelOps$.copy$1(ParallelOps.scala:164)
	at bloop.io.ParallelOps$.$anonfun$copyDirectories$8(ParallelOps.scala:189)
	at scala.runtime.java8.JFunction0$mcV$sp.apply(JFunction0$mcV$sp.java:23)
	at monix.eval.internal.TaskRunLoop$.startFuture(TaskRunLoop.scala:494)
	at monix.eval.Task.runToFutureOpt(Task.scala:586)
	at monix.eval.internal.TaskDeprecated$Extensions.runSyncMaybeOptPrv(TaskDeprecated.scala:128)
	at monix.eval.internal.TaskDeprecated$Extensions.$anonfun$coeval$1(TaskDeprecated.scala:303)
	at monix.eval.Coeval$Always.apply(Coeval.scala:1451)
	at monix.eval.Coeval.value(Coeval.scala:258)
	at bloop.io.ParallelOps$.$anonfun$copyDirectories$7(ParallelOps.scala:229)
	at monix.reactive.internal.consumers.ForeachAsyncConsumer$$anon$1.onNext(ForeachAsyncConsumer.scala:44)
	at monix.reactive.internal.consumers.LoadBalanceConsumer$$anon$1.$anonfun$signalNext$1(LoadBalanceConsumer.scala:218)
	at monix.execution.internal.InterceptRunnable.run(InterceptRunnable.scala:27)
	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)
	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
	at java.base/java.lang.Thread.run(Thread.java:1583)
#### Short summary: 

Unexpected error when copying <WORKSPACE>\.bloop\fireworks\bloop-internal-classes\classes-Metals-B3O...