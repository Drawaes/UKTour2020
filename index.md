## Welcome to the UK .NET Tour 2020

On Tuesday, January 28th 2020 at 6:30pm, members of the .NET community and the Microsoft .NET Team will be hosting multiple concurrent .NET events across the UK.

Preliminary locations and speakers (we may make some changes throughout 1/21).

If you are a **new speaker** (especially from underrepresented groups in tech) and would like to join us on stage, please ping organizers [Karel Zikmund](https://twitter.com/ziki_cz) and/or [Steve Gordon](https://twitter.com/stevejgordon) -- see our [tweet announcement](https://twitter.com/ziki_cz/status/1218204264092225536) for details.

| User Group / Location | Speakers & talks details |
|-----------------------|--------------------------|
| [London .NET User Group](https://www.meetup.com/London-NET-User-Group/events/267992448/) | [Olia Gavrysh](https://twitter.com/oliagavrysh) <br/> [Diego Colombo](https://twitter.com/colombod) - Introduction to .NET interactive in Jupyter notebooks |
| [Canary Wharf .NET User Group](https://www.meetup.com/Canary-Wharf-NET-User-Group/) | [Luce Carter](https://twitter.com/LuceCarter1) <br/> [Isaac Abraham](https://twitter.com/isaac_abraham) - SAFE Stack - The Pit of Success for Functional Web Programming |
| [.NET South East](https://www.meetup.com/dotnetsoutheast/events/267244937/) | [Bill Wagner](https://twitter.com/billwagner) <br/> [Karel Zikmund](https://twitter.com/ziki_cz) - Async demystified |
| [.NET Oxford](https://www.meetup.com/dotnetoxford/events/267776292/) | [David Wengier](https://twitter.com/davidwengier) <br/> [Matt Warren](https://twitter.com/matthewwarren) |
| [Reading .NET](https://www.meetup.com/reading-dot-net/) | [Irina Scurtu](https://twitter.com/irina_scurtu) <br/> [Eirik Tsarpalis](https://twitter.com/eiriktsarpalis) |
| [.NET South West](https://www.meetup.com/dotnetsouthwest/) | [Tim Seaward](https://twitter.com/timseaw) <br/> [Dean Ward](https://twitter.com/deanward81) |
| [Milton Keynes .NET](https://www.meetup.com/Milton-Keynes-NET-Meetup-Group/events/266750126/) | [Richard Campbell](https://twitter.com/richcampbell) |
| [DevOps Notts](https://www.meetup.com/DevOps-Notts/events/266765057/) | Vishal Vazkar <br/> [Martin Woodward](https://twitter.com/martinwoodward) |

We plan to record all talks and we will try to live-stream some of the talks - check this page few days before the event for details, or follow organizers on Twitter: [Steve Gordon](https://twitter.com/stevejgordon) and [Karel Zikmund](https://twitter.com/ziki_cz).



## About speakers and talks

Speakers listed in alphabetical order.

More details coming soon ...



### [Bill Wagner](https://twitter.com/billwagner)

Content developer for C# and .NET Core at Microsoft. Based in USA.



### [David Wengier](https://twitter.com/davidwengier)

Developer on the .NET Project System in Visual Studio team at Microsoft. Based in Melbourne, Australia.

A developer for the last 20 years, David has had experience in lots of different languages and environments, from cgi-bin scripts in Perl, to genetic algorithms in VB3, and Windows applications in COBOL. A series of terrible decisions, clearly, but he learnt in the end and now spends most of his time developing with .NET in C#, and enabling other developers to do the same.

David is is mostly interested in C#, good design and Lego Technic and Creator Expert cars. He can be found tweeting at @davidwengier, helping to organize the DDD Melbourne conference, and on about a half dozen different slacks.

**Abstract:** TODO



### [Dean Ward](https://twitter.com/deanward81)

Developer at Stack Overflow. Based in UK.



### [Diego Colombo](https://twitter.com/colombod) - Introduction to .NET interactive in Jupyter notebooks

Developer on the .NET Interactive team at Microsoft. Based in UK.

Over the past 20 years Diego has been working in lots of different industries using .NET technologies in video games, finance and robotics. With a researcher background he still gives presentations and lectures in Universities around Europe.

**Abstract:**

.NET interactive brings interactive development and notebooks experience to .NET developers. This talk will introduce the project and tools. We will cover the how to get started, the basics and some of the feature available out of the box.



### [Eirik Tsarpalis](https://twitter.com/eiriktsarpalis)

Developer on .NET Libraries team at Microsoft. Based in London, UK.



### [Irina Scurtu](https://twitter.com/irina_scurtu)

Microsoft MVP. Based in Romania.



### [Isaac Abraham](https://twitter.com/isaac_abraham) - SAFE Stack - The Pit of Success for Functional Web Programming

F# MVP, .NET and Azure consultant. Based in Germany.

Isaac Abraham is an. NET MVP and a .NET developer since .NET 1.0 with an interest in cloud computing and distributed data problems. He is the author of Get Programming with F# and is the director of Compositional IT. He specializes in consultancy, training and development, helping customers adopt high-quality, functional-first solutions on the .NET platform.

**Abstract:**

SAFE stack is an free, open-source, flexible end-to-end, functional-first stack for cloud-ready web applications that emphasizes type-safe programming. It allows you to develop web applications almost entirely in F#, without needing to compromise and shoehorn your codebase into an object-oriented framework or library, and without needing you to be an expert in CSS or HTML to create compelling, rich client-side web applications. This talk will demonstrate the value proposition behind the SAFE Stack, illustrating how we can develop unified client / server applications that take the best features of F# and apply them throughout the stack - such as type safety, succinctness, productivity and performance - whilst still integrating naturally with technologies and frameworks such as ASP .NET, JavaScript and React. You'll see how to create data driven server-side APIs quickly and easily, and then surface those APIs in a rich, responsive web application running in the browser, using a combination of .NET and JavaScript libraries and tools that come together beautifully. Lastly, we'll see how easily SAFE apps can be hosted on a cloud platform such as Microsoft Azure.



### [Karel Zikmund](https://twitter.com/ziki_cz) - Async demystified

Engineering manager on .NET Libraries team at Microsoft. Based in Redmond, USA.

Karel is on .NET team since 2005:
* Started as developer on Runtime/CLR components (7 years).
* Manager of reliability and performance team (incl. Quick Response Team) (3 years).
* Manager of .NET Native toolchain team (1 year).
* Now in the roles of community manager of CoreFX repo and manager of a few CoreFX/BCL areas like Networking (3 years).

Details: [https://karelz.github.io](https://karelz.github.io)

**Abstract:**

Do you struggle to fully understand async in C#? How it works and why?

I did. So I asked the best - the author of async, Stephen Toub. This talk is summary of the most interesting insights from him that helped me finally truly understand the magic behind async.

The talk will cover:
* History and evolution of asynchronous programming patterns in C# and their problems. Leading to async and demonstrating the "why" behind its design choices.
* Touch on the "how" it works behind the scenes.
* Reasons for customizing and hyper-optimizing async for high-performance (like Networking stack).
* Touch on related building block - ThreadPool.
* Hands on sync-over-async pattern and associated problems. Workarounds in your code if you hit it. Potential solutions in future .NET versions.



### [Luce Carter](https://twitter.com/LuceCarter1)

Microsoft MVP. Based in Manchester, UK.



### [Matt Warren](https://twitter.com/matthewwarren)

Microsoft MVP. Based in UK.



### [Olia Gavrysh](https://twitter.com/oliagavrysh)

Program manager on .NET team (WinForms, WPF and other areas). Based in Redmond, USA.



### [Richard Campbell](https://twitter.com/richcampbell)

Microsoft Regional Director. Host of .NET Rocks! Based in Canada.

### [Tim Seaward](https://twitter.com/timseaw)

.NET open source contributor. Based in UK.
