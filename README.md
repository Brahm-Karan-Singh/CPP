# CPP
|  <h1>[(1) Patterns1](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns1.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns1.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td>****</td>  </tr>  <tr>  <td> </td>  <td> **** </td>  </tr>  <tr>  <td> </td>  <td> **** </td>  </tr>  <tr>  <td> </td>  <td> **** </td>  </tr>  </tbody>  </table>              |  ```#include <iostream>  ```<br>```using namespace std;```<br>```  int main()```<br>```{```<br>```  int i=1,n,j=1;```<br>```  cin>>n;```<br>```  while(i<=n)```<br>```{ ```<br>``` j=1;```<br>```  while(j<=n)```<br>```{```<br>```  cout<<'*';```<br>```  j++; ```<br>``` }```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns2](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns2.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns2.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> 1234 </td>  </tr>  <tr>  <td> </td>  <td> 1234 </td>  </tr>  <tr>  <td> </td>  <td> 1234 </td>  </tr>  <tr>  <td> </td>  <td> 1234 </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n;```<br>```    cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```        int j=1;```<br>```while(j<=n)```<br>```{```<br>```cout<<j;```<br>```j++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns3](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns3.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns3.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> 1111 </td>  </tr>  <tr>  <td> </td>  <td> 2222 </td>  </tr>  <tr>  <td> </td>  <td> 3333 </td>  </tr>  <tr>  <td> </td>  <td> 4444 </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n;```<br>```    cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```        int j=1;```<br>```while(j<=n)```<br>```{```<br>```cout<<i;```<br>```j++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns4](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns4.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns4.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> 4321 </td>  </tr>  <tr>  <td> </td>  <td> 4321 </td>  </tr>  <tr>  <td> </td>  <td> 4321 </td>  </tr>  <tr>  <td> </td>  <td> 4321 </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n;```<br>```    cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```        int j=1;```<br>```while(j<=n)```<br>```{```<br>```cout<<(n-j+1);```<br>```j++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns5](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns5.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns5.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> 1 </td>  </tr>  <tr>  <td> </td>  <td> 12 </td>  </tr>  <tr>  <td> </td>  <td> 123 </td>  </tr>  <tr>  <td> </td>  <td> 1234 </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n;```<br>```    cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```        int j=1;```<br>```while(j<=i)```<br>```{```<br>```cout<<j;```<br>```j++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns6](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns6.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns6.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> 1 </td>  </tr>  <tr>  <td> </td>  <td> 12 </td>  </tr>  <tr>  <td> </td>  <td> 123 </td>  </tr>  <tr>  <td> </td>  <td> 1234 </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n,p;```<br>```    cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```        int j=1,p=i;```<br>```while(j<=i)```<br>```{```<br>```cout<<p;```<br>```j++;```<br>```p++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns7](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns7.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns7.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> 1 </td>  </tr>  <tr>  <td> </td>  <td> 23 </td>  </tr>  <tr>  <td> </td>  <td> 456 </td>  </tr>  <tr>  <td> </td>  <td> 78910 </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n,p=1;```<br>```    cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```        int j=1;```<br>```while(j<=i)```<br>```{```<br>```cout<<p;```<br>```j++;```<br>```p++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns8](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns8.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns8.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> ABCD </td>  </tr>  <tr>  <td> </td>  <td> ABCD </td>  </tr>  <tr>  <td> </td>  <td> ABCD </td>  </tr>  <tr>  <td> </td>  <td> ABCD </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n;```<br>```char ch;```<br>```cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```int j=1;```<br>```ch='A';```<br>```while(j<=n)```<br>```{```<br>```cout<<ch;```<br>```j++;```<br>```ch++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns9](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns9.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns9.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> ABCD </td>  </tr>  <tr>  <td> </td>  <td> BCDE </td>  </tr>  <tr>  <td> </td>  <td> CDEF </td>  </tr>  <tr>  <td> </td>  <td> DEFG </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n;```<br>```char ch;```<br>```cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```int j=1;```<br>```ch='A'+i-1;```<br>```while(j<=n)```<br>```{```<br>```cout<<ch;```<br>```j++;```<br>```ch++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns10](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns10.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns10.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> A </td>  </tr>  <tr>  <td> </td>  <td> BB </td>  </tr>  <tr>  <td> </td>  <td> CCC </td>  </tr>  <tr>  <td> </td>  <td> DDDD </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n;```<br>```char ch;```<br>```cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```int j=1;```<br>```ch='A'+i-1;```<br>```while(j<=i)```<br>```{```<br>```cout<<ch;```<br>```j++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|


|  <h1>[(1) Patterns11](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns11.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns11.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> A </td>  </tr>  <tr>  <td> </td>  <td> BC </td>  </tr>  <tr>  <td> </td>  <td> DEF </td>  </tr>  <tr>  <td> </td>  <td> GHIJ </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n;```<br>```char ch='A';```<br>```cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```int j=1;```<br>```while(j<=i)```<br>```{```<br>```cout<<ch;```<br>```j++;```<br>```ch++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns12](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns12.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns12.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> D </td>  </tr>  <tr>  <td> </td>  <td> CD </td>  </tr>  <tr>  <td> </td>  <td> BCD </td>  </tr>  <tr>  <td> </td>  <td> ABCD </td>  </tr>  </tbody>  </table>              |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```    int n;```<br>```char ch;```<br>```cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```    {```<br>```int j=1;```<br>```ch='A'+n-i;```<br>```while(j<=i)```<br>```{```<br>```cout<<ch;```<br>```j++;```<br>```ch++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns13](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns13.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns13.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;* </td>  </tr>  <tr>  <td> </td>  <td> &nbsp;&nbsp;&nbsp;&nbsp;** </td>  </tr>  <tr>  <td> </td>  <td> &nbsp;&nbsp;*** </td>  </tr>  <tr>  <td> </td>  <td> **** </td>  </tr>  </tbody>  </table> |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```int n;```<br>```cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```{```<br>```int j=1;```<br>```while(j<=(n-i))```<br>```{```<br>```cout<<' ';```<br>```j++;```<br>```}```<br>```int k=1;```<br>```while(k<=i)```<br>```{```<br>```cout<<'*';```<br>```k++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns14](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns14.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns14.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> **** </td>  </tr>  <tr>  <td> </td>  <td> *** </td>  </tr>  <tr>  <td> </td>  <td> ** </td>  </tr>  <tr>  <td> </td>  <td> * </td>  </tr>  </tbody>  </table> |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```int n;```<br>```cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```{```<br>```int j=1;```<br>```while(j<=(n-i+1))```<br>```{```<br>```cout<<'*';```<br>```j++;```<br>```}```<br>```int k=1;```<br>```while(k<i)```<br>```{```<br>```cout<<' ';```<br>```k++;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|

|  <h1>[(1) Patterns15](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns15.cpp)</h1> |<h1>[CODE](https://github.com/ArshdeepSahni/CPP/blob/master/Patterns15.cpp)</h1>|
|---|---|
|<table style="width:max-content"> <tbody> <tr> <td colspan="2"> <table>`CUSTOM EXAMPLES`</table></td> <tr> <tr>  <td> `INPUT` </td>  <td>`OUTPUT`</td>  </tr> <tr>  <td> 4 </td>  <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1 </td>  </tr>  <tr>  <td> </td>  <td> &nbsp;&nbsp;&nbsp;&nbsp;121 </td>  </tr>  <tr>  <td> </td>  <td> &nbsp;&nbsp;12321 </td>  </tr>  <tr>  <td> </td>  <td> 1234321 </td>  </tr>  </tbody>  </table> |```#include <iostream>```<br>```using namespace std;```<br>```int main()```<br>```{```<br>```int n;```<br>```cin>>n;```<br>```int i=1;```<br>```while(i<=n)```<br>```{```<br>```int j=1;```<br>```while(j<=(n-i))```<br>```{```<br>```cout<<' ';```<br>```j++;```<br>```}```<br>```int k=1;```<br>```while(k<=i)```<br>```{```<br>```cout<<k;```<br>```k++;```<br>```}```<br>```int p=k-2;```<br>```while(p>0)```<br>```{```<br>```cout<<p;```<br>```p--;```<br>```}```<br>```i++;```<br>```cout<<endl;```<br>```}```<br>```return 0;```<br>```}```|
