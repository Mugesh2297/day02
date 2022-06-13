1. Write a blog on Difference between HTTP1.1 vs HTTP2
Ans: 
HTTP Stands For Hypertext Transfer Protocol, And It Is The Basis For Almost All Web Applications. More Specifically, HTTP Is The Method Computers And Servers Use To Request And Send Information. For Instance, When Someone Navigates To Guvi.Com On Their Device, Their Web Browser Sends An HTTP Request To The Guvi Servers For The Content That Appears On The Page. Then, Guvi Servers Send HTTP Responses With The Text, Images, And Formatting That The Browser Displays To The User.
The First Usable Version Of HTTP Was Created In 1997 This First Version Of HTTP Was Called HTTP/1.1. This Version Is Still In Use On The Web. In 2015, A New Version Of HTTP Called HTTP/2 Was Created.
HTTP/2 Solves Several Problems That The Creators Of HTTP/1.1 Did Not Anticipate. In Particular, HTTP/2 Is Much Faster And More Efficient Than HTTP/1.1. One Of The Ways In Which HTTP/2 Is Faster Is In How It Prioritizes Content During The Loading Process.
In HTTP/2, Developers Have Hands-On, Detailed Control Over Prioritization. This Allows Them To Maximize Perceived And Actual Page Load Speed To A Degree That Was Not Possible In HTTP/1.1.
HTTP/1.1 Loads Resources One After The Other, So If One Resource Cannot Be Loaded, It Blocks All The Other Resources Behind It. In Contrast, HTTP/2 Is Able To Use A Single TCP Connection To Send Multiple Streams Of Data At Once So That No One Resource Blocks Any Other Resource. HTTP/2 Does This By Splitting Data Into Binary-Code Messages And Numbering These Messages So That The Client Knows Which Stream Each Binary Message Belongs To.
Small Files Load More Quickly Than Large Ones. To Speed Up Web Performance, Both HTTP/1.1 And HTTP/2 Compress HTTP Messages To Make Them Smaller. However, HTTP/2 Uses A More Advanced Compression Method Called HPACK That Eliminates Redundant Information In HTTP Header Packets.



2. Write a blog about objects and its internal representation in Javascript
Ans:Objects Are Important Data Types In Javascript. Objects Are Different Than Primitive Datatypes (I.E. Number, String, Boolean, Etc.). Primitive Data Types Contain One Value But Objects Can Hold Many Values In Form Of Key: Value Pair. These Keys Can Be Variables Or Functions And Are Called Properties And Methods, Respectively, In The Context Of An Object. For Instance, A Cup Is An Object, With Properties. A Cup Has A Color, A Design, Weight, A Material It Is Made Of, Etc. The Same Way, Javascript Objects Can Have Properties, Which Define Their Characteristics.
Every Object Has Some Property Associated With Some Value. These Values Can Be Accessed Using These Properties Associated With Them.
var mycup {
color : “Red”,
design : “cone”,
weight : 50,
material : “Plastic”
}
After Creating mycup Object, The Value Inside The Object Can Be Accessed Using Keys.
i.e.
console.log(mycup.color);
Output: Red


