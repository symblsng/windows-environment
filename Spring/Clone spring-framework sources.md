Add the aliyun repositories:

    repositories {
        maven { url "http://maven.aliyun.com/nexus/content/groups/public" }
        maven { url "http://maven.aliyun.com/nexus/content/repositories/jcenter" }
        mavenCentral()
        maven { url "https://repo.spring.io/libs-release" }
        maven { url "https://repo.spring.io/milestone" } // Reactor
    }
    
References:
  + https://blog.csdn.net/panchang199266/article/details/100548710
