# mavenrepo
sdk

引用库时请在项目根节点的build.gradle文件中添加如下资源地址
allprojects {
    repositories {
        maven { url "https://raw.githubusercontent.com/chengkaizone/mavenrepo/master" }
    }
}
