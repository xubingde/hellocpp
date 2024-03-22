# helloC++

#### Description
A tool that can easily use C++ to generate general code, manage and automatically generate source code.

HelloC++ allows you to simplify the process of writing code to the most primitive "data structure + algorithm", and focus your time and energy on how to solve problems instead of struggling with C++ syntax every day.

This is a small standalone tool that you should use as a C++ source code text editor, not as a replacement for other integrated IDE tools.Even though it is a small tool, it can still easily manage hundreds of thousands of lines of source code, and provides good support for adding, deleting, moving source code, refactoring named objects, etc. It centrally manages .h and .cpp files, turning the "flat" source code text on the paper into a "three-dimensional" object.

#### Project Objectives:

1. Enter a custom name only once, such as a class name or a function name. If there is any change, all related positions will be automatically modified;
2. Conveniently adjust the field order, and the corresponding source code of constructors, destructors, operator overloads, etc. can be adjusted accordingly;
3. Automatically generate == != < <= > >= swap() toString() fromString() and other source codes, and maintain them in a way that is convenient for management. It also supports protected source code generation and type conversion in the inheritance system.
4. Support generating template function and template class source code;
5. Support generating Header-only source code;
6. Even with all the above functions, you can still fully control your own source code, that is, if you are not satisfied, you can replace, insert, and delete all the automatically generated source codes above with your own additional code, and compare them with Conduct this process in an administratively convenient manner.
7.  Hundreds of thousands or millions of lines of C++ source code can be easily managed using the HelloC++ tool. All source code of this project is automatically generated and managed by this tool.

#### Installation

1.  Download hellocpp.zip, unzip it, and double-click hellocpp.exe to run it directly. The default font is Microsoft YaHei Mono monospaced font. It is recommended to install the font. Double-click the file MSYHMONO.ttf and click "Install". Download link: https://pan.baidu.com/s/1t3w7lwiJADPDabq5skZfLg?pwd=uqg3 Extraction code: uqg3

2. To compile the source code, first install Qt 5.12.12, msvc++ vs2019 or higher, and the project file is a Qt Creator file.

3. If you just want to view or modify the source code, you only need to download hellocpp.zip, run hellocpp.exe, and open the folder ./hellocpp/xdf/ to directly view the annotated source code (the source code in the project has no annotations), no need Install Qt and vs2019.

#### Instructions

1.  You must create a folder yourself before saving the source code. For example, if your source code is saved in the D:\hello folder, you need to manually create the following 4 folders: D:\hello, D:\hello\src, D :\hello\test, D:\hello\xdf, Fill in the dir input-textBox: D:\hello\

2.  Only 0 or 1 class is allowed for a pair of .h .cpp files. 0 classes are similar to C language, with only codes such as functions, macros and global variables.

3.  There are three file types: .cpp .hpp .c. If it is .hpp, it means generating a header-only source code.

4.  The source code for this project has been saved as .xdf files, all placed in the ./xdf folder.

5.  Functions such as adding, moving and copying, adding, deleting and moving line items, adding and deleting following source code, etc. are in the right-click menu of the mouse.
![image](https://github.com/xubingde/hellocpp/assets/9046560/f3b9d19f-2e2f-41a7-bc7e-f597a5269e56)

6.  If the function return type is auto, prepend the contents of the function's Return Type with ->. For example ->int or template function -> T or direct input ->

7.  Most list boxes and source code input boxes can be resized with the mouse and hidden by dragging.

8.  If the automatically generated toString() and fromString() are used, the C++17 version is required (default C++11), and #include "icode.h".

9.  Fields are added or removed first in the Field General tab, and then getter setter functions are added or removed in the Field Action tab.

#### User manual

https://gitee.com/xubingde/hellocpp
