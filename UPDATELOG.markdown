# Update Log 升级日志
* Ver 1.01.20120110 : Several Enhancements
    - Added Support for initial rotation in comments
	  添加了弹幕旋转的支持
	- Added Limited Support for filtering (by type, by property, by regex)
	  添加了有限的弹幕过滤能力（按类型、属性或正则表达式过滤）
	- Added limited support for default styles
	  添加了部分支持
	- Enhanced CSS for a better effect on Webkit Browsers
	  修正了CSS使得在Webkit系浏览器上显示更好且速度更流畅！
	- Added CORSPRoxy to aid Cross-Domain Resource Requests (to fetch comment lists)
	  添加了CORS代理程序（PHP）来支援跨域资源请求（如从A/B站获取弹幕列表）
	- Some code revisions
	  修正一些性能问题
* Ver 1.00.20111208 : Initial Release
	首次发布
	
# Browser Support 浏览器支持

*IE 4-5* : None - 不支持
	Lack of support for DHTML
*IE 6* : Maybe - 不清楚
	Some functionality _might_ be supported by IE 6 if _you are lucky_.
	IE6 is not supported and we will be making no efforts to support it.
*IE 7/8* : Minimal - 欠支持
	Supported: scroll, top, bottom, reverse, positioned
	Unsupported: effects, opacity, rotation, highlighting
*Webkit (Chrome/Safari)* : Most - 最多
	Webkit series supports the biggest set of functionality and better enhancements.
*Gecko (Firefox)* : A lot - 很多
	Basic and extended functions, though not enhanced.
*Presto (Opera)* : A lot
	Basic and extended but few enhancements. Lack of testing done here.