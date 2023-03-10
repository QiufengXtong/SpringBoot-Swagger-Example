SpringBoot 整合 Swagger3 示例

# 这是一个简单的演示项目，使用步骤如下：
1. 拉取项目
2. 启动项目，并访问`http://127.0.0.1:8088/swagger-ui/index.html

# Swagger 常见注解说明
`@EnableOpenApi`：启用`Swagger`。
`@ApiModel`：描述实体类。
`@ApiModelProperty`：描述字段。
`@Api`：描述`Controller`控制类。
`@ApiOperation`：描述每一个`Mapping`控制器。