﻿<!--
 * @Author: suyang
 * @Date: 2020-03-01 15:09:45
 * @Description: In User Settings Edit
 * @FilePath: \inventory\README.md
 -->
# inventory-fe

## views代码代码具体说明
```
登录 Login
```
```
首页 Index
  头部
  导航栏
  TAB页（二级子路由）
    基本资料 BaseInfo
      商品档案，商品计量单位，价格名称
      客户档案，供货商档案 （这俩内容一样，可以考虑复用一个ui，包括模态框）
      地区档案，分支机构，部门档案，职员档案，
      存货仓库，角色管理，账户选择
        新增编辑模态框


    单据管理 BillManagement
      进货单， 销售单，退货单 (这三个共用一个ui，只是标题和发送的请求不一样)
      单据查询 
      基本资料的选择模态框

    管理设置 ManagementSetting


    日志 Log


```
