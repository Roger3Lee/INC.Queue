# INC.Queue

An implement queue basic on .net framwork C# language

You can used it like that:

```C#
var manager = new QueueManager(new QueueConfirguration(5, 10000, 1));
manager.Start();
manager.AddJob(new Job(() =>{Console.WriteLine(....);}))
```
