# CHANGELOG

## 2022/08/09 
### Rel-AL 0.10.1 ROUTINE UPDATE
**FIX**
- 或许修复了部分ViewPager的Fragment页面没有attach在activity上时会崩溃的问题
### Rel-AL 0.10.2 ROUTINE UPDATE
**FIX**
- 修复了个人页面头像框错位问题

## 2022/08/12
### Rel-AL 0.12.0 FEATURE UPDATE
**FEAT**
- 查看收藏夹列表
- 查看收藏夹内的视频列表
- 查看关注分组列表
- 查看关注分组里的用户列表
### Rel-AL 0.12.1 ROUTINE UPDATE
**FIX**
- 修复mid过长崩溃问题

## 2022/08/13
### Rel-AL 0.12.3 ROUTINE UPDATE
**FIX**
- 修复视频列表在某些设备上封面显示效果不好的问题
- 修复首页/视频详情页的几个页面加载完成之前滑走会导致加载中断并且无法重新加载的问题
- 修复了另一个地方的mid过长导致崩溃的问题

**CHANGE**
- 视频播放页换成Exoplayer官方提供的PlayerView，或许可以解决一些莫名其妙的问题

## 2022/08/14
### Rel-AL 0.12.4 ROUTINE UPDATE
**FIX**
- 修复了一些可能导致崩溃的bug
- 修复了动态列表下拉刷新时会自动下滑的bug
- 
**LOGIC**
- 新增了获取用户access_key的方法
- 改变了一些网络请求方法的回调逻辑
- 
**KNOWN BUGS**
- 动态刷新完成后，可能不会自己回到顶部
- 点击无网络页面的刷新按钮会导致崩溃
- 动态详情和无网络页面有渲染问题，可能导致花屏、重影等问题

## 2022/08/15
### Rel-AL 0.12.5 FEATURE UPDATE
**FEAT**
- 新增“UP主觉得很赞”标签
- 在评论列表中显示的楼中楼会用粉色来区分up主

**FIX**
- 修复了UP主标识会在其他人头上显示的BUG
- 修复了动态评论只能获取第一页的BUG

**KNOWN BUGS**
- 动态评论页在触发加载更多时有几率崩溃
- 动态评论页在触发加载更多时有几率重复

## 2022/08/16
### Rel-AL 0.12.6 ROUTINE UPDATE
**FIX**
- 修复了因修改密码等原因被强制下线后会崩溃的Bug

**LOGIC**
- 更新了登录相关逻辑，实现了access key的保存
