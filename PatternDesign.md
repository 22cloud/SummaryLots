##设计模式
    
    设计模式（Design Pattern）是一套被反复使用、多数人知晓的、经过分类编目的、代码设计经验的总结。
    
    目的：使用设计模式是为了可重用代码、让代码更容易被他人理解、保证代码可靠性。
    
###单例模式
    
    有些对象我们只需要一个
    	比如：配置文件、工具类、线程池、缓存、日志对象等
    	
    如果创造出多个实例，就会导致许多问题
    	比如占用过多资源，不一致的结果等
    	
    单例模式保证整个应用中某个实例有且只有一个
    
    饿汉模式与懒汉模式的区别：
    饿汉模式：特点是加载类时比较慢，但运行时获取对象的速度比较快（因为在加载类时就已经创建了对象），线程安全的
	懒汉模式：特点是加载类时比较快，但运行时获取对象的速度比较慢（因为在加载类时并没有创建对象），线程不安全的
