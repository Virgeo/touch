项目中实现的功能：
1. 使用mybatis-generator生成xml与entity，通过自定义Plugin取消默认setter()与getter()方法，并添加lombok的@Data注解
2. 使用mybatis默认的Interceptor对sql进行拦截，为createTime、updateTime字段自动添加日期时间
3. 使用mybatis默认的Interceptor对sql进行拦截，添加sql日志打印耗时打印功能
4. 理解mybatis插件原理，通过学习代理模式对mybatis拦截器进行简单实现