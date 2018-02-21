mapper 存放dao中每个方法对应的sql，在这里配置，无需写daoImpl
spring 存放spring相关的配置文件，有dao service web三层

dao 数据访问层 数据库操作 文件读写操作
entity POJO 封装dao层取出来的数据为一个对象
dto 数据传输层 用于service层与web层之间传输
service 业务逻辑接口
serviceimpl 业务逻辑接口的实现
web controller 控制层

dao包中为接口 不需要实现 、MyBatis会自动帮我们实现 只需要编写mapper