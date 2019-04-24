# aspnettest


**Welcome**
----------

1. test d

```C#

// Program.cs
public class Program
{
    public static void Main(string[] args)
    {
        CreateBuildWebHost(args).Build().Run();
    }

    public static IWebHostBuilder CreateBuildWebHost(string[] args) =>
        WebHost.CreateDefaultBuilder(args)
            .UseStartup<Startup>()
            //.UseUrls("http://*:58080")
            .UseUrls("http://127.0.0.1:58080");
}

```

2. second
3. third
