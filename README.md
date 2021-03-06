# 欢迎使用 Stonefield Database Toolkit (SDT)

 翻译：xinjie    2020.01.15
 
 [英文版](https://github.com/vfp9/StonefieldDatabaseToolkit/blob/master/README_EN.md)

Stonefield Database Toolkit (SDT) 是由 Doug Henning 开发的功能强大的工具，该工具由 Stonefield Software Inc 销售超过20年。2020年元月，StoneField Software 决定对其开源，免费提供给所有 Microsoft® Visual FoxPro™ 开发者使用。

SDT 是一个为开发者提供的数据库管理工具，以便在应用程序的开发和运行过程中提供帮助。

SDT 在以下三个方面为开发者提供帮助：

* 它是 VFP 提供的管理数据对象功能的增强版。

* 它提供了为数据库对象定义扩展的属性，并且可以在运行时定义或获取这些设置的能力。

* 它包含一个类库，你可以将其添加到你自己的应用中，以便在运行时提供数据的管理功能。这包括：重建索引、修复坏表、以及在客户端创建和更新表结构的能力。

通过使用 SDT，您将获得以下收益：

* 减少开发时间：为什么要重复造轮子？SDT 附带的数据驱动程序使您不必编写高级用户所需的表维护功能。可以将其包含在您开发的每个应用中，而无需进行任何更改。你需要做的，就是将其添加到您的项目中，然后在你需要的地方（菜单、表单、程序中）调用它，剩余的工作就交给其处理就OK了。

* 减少维护工作：术语“数据驱动”指使用数据字典驱动应用程序。更改数据字典，就可以使应用的很多方面无需编程即可实现自动调整。

* 自动文档编制：VFP随附的文档编制向导可以对您的应用程序文件进行文档编制，但仅限于数据文档编制。SDT可以自动生成高质量的文档，完整描述表和视图，已经它们的字段、索引和扩展属性。

SDT 随附完整的源代码。它可以安装在计算机或网络上的任何目录中。注意：如果您的计算机上安装了早期版本的SDT，则可能需要将此版本安装在其他目录中，以避免覆盖以前的版本。

您将在安装文件的目录中找到两个子目录： 

* SDT: SDT 的专用文件。

* SFCOMMON: 所有 StoneField 产品使用的公共文件。

在 SDT 子目录中包含以下文件：

* REINDEX.PRG, REPAIR.PRG, and UPDATE.PRG: SDT Reindex（），Repair（）和Update（）方法的封装。有关这些程序的使用，请参见“教程”一章。

* SDT.APP, SDT.PJX, and SDT.PJT: SDT 开发版以及创建它的项目文件。

* SDT.CHM: SDT 帮助文件。

除了这些文件之外，您还将找到SDT子目录的五个子目录：

* DBCX: 包含 DBCX 的文档。

* HTMLHELP: SDT.CHM 的源文件，它由 West Wind HTML Help Builder 使用并最终编译为 SDT.CHM 。

* SOURCE: 主应用程序(SDT.APP)的源代码以及可以被包含在你应用中的可视类库。

* TUTORIAL: SDT 教程文件。

* UTILITY: 实用程序和支持文件。有关这些实用程序的信息，请参见 SDT.CHM 中的“实用程序功能”部分。

注意：SDT 随附的所有源代码都是在 VFP9 中编译的。如果使用早期版本的 VFP，则应重新编译所有文件。最简单的方法是在SDT目录中打开SDT项目，单击“编译”按钮，选中“重新编译所有文件”选项，然后选择“重新编译项目”。
