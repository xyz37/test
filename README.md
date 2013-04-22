MySql SimpleMembership Provider for ASP.NET MVC 4
=================================================

MySql SimpleMembership Provider for ASP.NET MVC 4
  with Entity Framework 5.x CodeFirst


Projects information
--------------------

##### Libraries
* MySql.Data.Extension : MySql Entity Framework Extension for Code First
* MySql.Web.Extension : MySql SimpleMembership Provider for Code First

##### Samples
* SimpleMembershipTest : ASP.NET MVC 4 Simple Membership sample web site
* SimpleMembership.Dac : SimpleMembership Data access control

[Daring Fireball: Markdown Syntax Documentation](http://daringfireball.net/projects/markdown/syntax)

[Github Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#wiki-code)

&copy;
> test

    4 space

[Goto my blog link](http://xyz37.blog.me)

<table>
    <tr>
        <td colspan="2">Foo</td>
    </tr>
    <tr>
        <td>Bar</td>
        <td>Bar</td>
    </tr>
</table>


```xml
<connectionStrings>
	<add name="MySqlEFTestDbContext"
		 connectionString="server=localhost;port=3306;database=mysqleftest;User Id=dev;Password=thePassword;Persist Security Info=True;"
  		 providerName="MySql.Data.MySqlClient" />
</connectionStrings>
```

```java
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace MySqlEFTest
{
  class Program
	{
		static void Main(string[] args)
		{
			using (var db = new MySqlEFTestDbContext())
			{
				var count = db.Users.Count();

				Console.WriteLine("UserCount: {0}", count);
			}
		}
	}
}
```


