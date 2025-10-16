@Library("/lib") _

// This shows a simple build wrapper example, using the AnsiColor plugin.
node {
    stage("run") {
        extra = load("extra.groovy")
        var foo = new com.markvr.Foo()
        println("Say: " + foo.bar())
    }
}