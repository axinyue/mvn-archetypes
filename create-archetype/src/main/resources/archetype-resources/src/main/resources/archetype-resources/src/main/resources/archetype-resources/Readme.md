## 创建自己的原型
1. 放置一个maven工程到这个路径
2. 修改pom.xml中的 groupId,artifactId,version 为 ${groupId},${artifactId},${version}
3. 运行mvn install
4. 在Windows->Maven->Archetype, Add Local Catalog, 然后选中 ~/.m2/repository/archetype-catalog.xml.
5. 通过新建maven项目,就可以使用自己的原型了,如果是SNAPSHOP版,记得勾选SNAPSHOP.