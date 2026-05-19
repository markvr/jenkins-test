@Library("_local_@lib") _

node {
    stage("run") {
        print("Started,sleeping for 60sec")
        sleep(60)
        def foo = new com.markvr.Foo()
        println("Say: " + foo.bar())
    }
}

// 4