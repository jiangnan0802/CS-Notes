# ODBC 和 JDBC 的关系

## ODBC是什么

ODBC（Open Database Connectivity，开放数据库互连）提供了一种标准的API（应用程序编程接口）方法来访问数据库管理系统（DBMS）。这些API利用SQL来完成其大部分任务。ODBC本身也提供了对SQL语言的支持，用户可以直接将SQL语句送给ODBC。ODBC的设计者们努力使它具有最大的独立性和开放性：与具体的编程语言无关，与具体的数据库系统无关，与具体的操作系统无关。



## JDBC 是什么

Java数据库连接，（Java Database Connectivity，简称JDBC）是Java语言中用来规范客户端程序如何来访问数据库的应用程序接口，提供了诸如查询和更新数据库中数据的方法。JDBC也是Sun Microsystems的商标[1]。JDBC是面向关系型数据库的。



## 主要区别



| ODBC                                                         | JDBC                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ODBC Stands for Open Database Connectivity.                  | JDBC Stands for java database connectivity.                  |
| Introduced by Microsoft in 1992.                             | Introduced by SUN Micro Systems in 1997.                     |
| We can use ODBC for any language like C,C++,Java etc.        | We can use JDBC only for Java languages.                     |
| We can choose ODBC only windows platform.                    | We can Use JDBC in any platform.                             |
| Mostly ODBC Driver developed in native languages like C,C++. | JDBC Stands for java database connectivity.                  |
| For Java applications it is not recommended to use ODBC because performance will be down due to internal conversion and applications will become platform Dependent. | For Java application it is highly recommended to use JDBC because there we no performance & platform dependent problem. |
| ODBC is procedural.                                          | JDBC is object oriented.                                     |



## 参考资料

- [ODBC 维基百科](https://zh.wikipedia.org/wiki/ODBC)

* [JDBC 维基百科](https://zh.wikipedia.org/wiki/Java%E6%95%B0%E6%8D%AE%E5%BA%93%E8%BF%9E%E6%8E%A5)

* [DIFFERENCE-ODBC-JDBC](https://www.geeksforgeeks.org/difference-odbc-jdbc/)
