# FlyGo_Dependency_B
文档地址：https://www.flygo520.com/docs/maven/maven-1alv8716d6akq

# 创建Maven父项目

1、右键`New` -> 选择`Project...`

![创建父项目 步骤1](https://www.flygo520.com/uploads/maven/images/m_29b83fe3f04034389ddc6b78293e9d58_r.png#size=360x0)

2、选择 `Maven Project` -> 选择 `下一步`

![创建父项目 步骤2](https://www.flygo520.com/uploads/maven/images/m_f05cb2cf736c817a83b0a05f4f888bd2_r.png#size=360x0)

3、勾选`Create a simple project  (skip archetype selection)`-> 选择`下一步`

![创建父项目 步骤3](https://www.flygo520.com/uploads/maven/images/m_88023f621995d513fd20c9440faf3ab5_r.png#size=360x0)

4、填写相关信息，特别注意，父类项目有且只能选择 `Packaging` 为 `pom` 类型。

![创建父项目 步骤3](https://www.flygo520.com/uploads/maven/images/m_3c297ce2196119e9660ebe4a120397fe_r.png#size=360x0)

# Maven父项目目录结构

![父类项目目录结构](https://www.flygo520.com/uploads/maven/images/m_300aa5978cbb4ad50842129b01b82eed_r.png#size=360x0)

# 创建Maven 子项目

1、右键`New` -> 选择`Project...`

![创建子项目 步骤1](https://www.flygo520.com/uploads/maven/images/m_29b83fe3f04034389ddc6b78293e9d58_r.png#size=360x0)

2、选择 `Maven Module` -> 选择 `下一步`

![创建子项目 步骤2](https://www.flygo520.com/uploads/maven/images/m_19ff59086465e7ee67183dff61d8d6b1_r.png#size=360x0)

3、勾选`Create a simple project  (skip archetype selection)`-> 填写`Module Name` 子项目名称 ->  选取`Parent Project` 父项目 -> 选择`下一步`

![创建子项目 步骤3](https://www.flygo520.com/uploads/maven/images/m_373c2475a6218feb44accf348f3a0deb_r.png#size=360x0)

4、填写子项目相关信息。

![创建子项目 步骤4](https://www.flygo520.com/uploads/maven/images/m_55a46b342b8943dcd1c8fdf60de9aff0_r.png#size=360x0)

# 子项目及父项目目录结构的变化

1、子项目目录结构的变化

![子项目目录结构](https://www.flygo520.com/uploads/maven/images/m_ec741fe6e6c818de527fc674860a74c8_r.png#size=360x0)

2、父项目目录结构的变化

父项目 `pom.xml` 包含 子项目模块的声明
目录中包含子项目文件目录
```bash
<modules>
	<module>FlyGo_Child_B</module>
</modules>
```
![父项目目录结构](https://www.flygo520.com/uploads/maven/images/m_39a58e9ec291b576f1ed99e3fb513da6_r.png#size=360x0)

# 演示Demo源码地址

