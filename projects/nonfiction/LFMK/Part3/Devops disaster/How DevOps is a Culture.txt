### DevOps and the Culture of Contribution

/images/60090282524__46DCB812-CBBE-4D52-A71E-1F369E847FFE.jpeg
`Near the end of a dead-end walkway at Hollywood Studios, a Custodian created a Mickey out of fallen leaves`

If you ask ten different software engineers what "DevOps" is, you'll get ten different answers. Many of the answers will focus on tools and development methods that focus on things like "Continuous integration." If you're lucky, one of the software engineers will tell you *"DevOps is a culture."*

Traditionally, software product efforts are broken up into clearly separate teams - a Development team which builds the product, and an Operations team which runs and supports the developed product. Development deals with new features and fixing long-standing bugs, Operations deals with getting servers to run the product on and dealing with customer's issues. 

The benefits of this traditional organization structure are primarily business- and financial- management focused. It's nice to have a clear understanding of who works on building the thing, and who works on keeping it running. It makes the accounting very clean, you can see how much development costs and how much operation costs, and make decisions accordingly. 

The downsides of this traditional organization structure are immense, but, *critically*, hard to measure with traditional business- and financial- management approaches. The biggest downside is that the people building the product are insulated from any and all problems the product may have in day-to-day operation. 

The Development team builds something, and they "throw it over the wall" to Operations. Operations installs it and runs with it, and any problems that come up are now "Operation's problems" and the Development team continues work on the next release, irrespective of what's happening in on the operational side.

This situation then causes blame-pointing, and impacts the overall quality of the product. 

The software industry's response to this situation is "DevOps," literally the combination of Development and Operations. The goal of DevOps is to remove the fence between these two pieces of the organization and therefore improve the situation.

#### "DevOps is tools!"

When engineers hear that the transition between Development and Operations needs to be improved, they build tools - and wow, there are a *lot* of "DevOps" related tools and "best practices" out there. 

From here we can dive deeply into all aspects of modern software development, but those topics are covered very well in other books. We're just going to touch on one type of tool here.

The single biggest concept and toolset this "DevOps" approach has given us is "Continuous Integration" or CI. CI tools automatically integrate any developer's change to the software with the system and all the other changes that have been made in a testing environment. Doing this helps to find conflicts or errors caused by pulling the developer's change in. This effectively pulls the developer closer to the "Operational" environment, because their changes get integrated into the rest of the system (in an operational-like, test environment) automatically after the change is made. 

This is why most of the software developers you ask about "DevOps" will respond to you with descriptions of tools. Their interaction with "DevOps" is the automation that happens after they make a change to the code. 

Previously, developers would have to take these integration steps themselves, manually. This would result in developers spending time on routine integration tasks, and integrations not being performed regularly resulting in more, harder-to-fix problems once the integration of many changes was performed. Doing these steps with automation solves a ton of problems, and completely circumvents entire classes of problems such as mistakes when manually performing the integration procedure and problems due to integrating many changes at the same time. This automation also allows the development team to scale up without the integration problems that come with more developers when all of this is manual. 

While the automation the developers interact with is definitely an element of DevOps, engineers with this view are missing the bigger picture. But even so, there are lessons to learn from the DevOps tools and methods:

- Wherever practical, automate. Where not practical, have a well defined process in order to limit unexpected outcomes.
- Make processes scalable.
- 

#### "DevOps is a management nightmare!"

While engineers build tools to address the "DevOps" need, managers attempt to address it with the tools they have. When an engineer advocates for "DevOps" to a manager on a software project, the manager usually understands the request as a request to organizationally merge the Development and Operations teams. Which is an absolute nightmare. 

DevOps, fully embraced at this raw, conceptual, organizational-only level, is a world-breaking departure from traditional business models.

No sane manager would say that the factory worker who assembled your car should also be the mechanic at your dealership and the person who puts gas in it. But according to pure, conceptual-level DevOps... *This is the way.* 

Software projects don't have the physical restrictions that physical projects do, but even there, mashing together roles and responsibilities have real, world-breaking impacts.

Because of the world-breaking nature of pure DevOps, there is no perfect way to implement it. Additionally, every product and situation is different. Therefore DevOps concepts have to be designed and applied thoughtfully and individually in each effort. This is another management-breaking issue, because project managers are used to implementing known solutions, with known costs, and known benefits. "DevOps" isn't that. 

The manager who sees "DevOps" as something that can be implemented in one effort and never worked again is missing the bigger picture. 

"DevOps" is too ambiguous to know how to determine its cost - and while there are some apparent benefits to having the development and operations teams work closely together, the *financial* benefits are pretty ambiguous also. This situation tends to trap organizations: They know they want to "do DevOps" but can't figure out what it will cost, or what benefit they will get, or when they will be done doing it. Organizations can't figure out how to "Buy the DevOps." 

... Which is only natural, because "DevOps" isn't something you can buy. 

DevOps isn't a toolset or an organizational change. It is, as the one wise software engineer said, a *culture* first, which may then drive tool or organizational changes.

#### Culture of Contribution: Software

The culture that DevOps promotes in the software development world can be described as enabling everyone to contribute, regardless of role. Developers can contribute to the Operations team by seeing how their changes impact the product in an operational environment and adjusting the changes to make things better; the Operations team can contribute to development, because the toolsets used enable anyone to branch the source code and contribute in a clean, review-able way. Good ideas are captured, and change-controlled in a much more collaborative, less blame-pointy way. 

Enabling more people in the organization to contribute to the product (typically) has positive impacts. The good ideas get integrated and deployed, the not-so-good ideas get captured so they can be iterated and improved upon - or used as examples of what not to do. In either case, the additional contributions are  positive. 

Indeed, the rise of these concepts and toolsets has enabled (and subsequently been fed by) the rise of open source software. Global collaboration on open source software has brought humanity tools that simply would not be possible with traditional, non-collaborative development. 

*"Enable everyone in your organization to contribute to the product and experience you deliver to the customer."*

#### Culture of Contribution: Everywhere else
<TODO> Describe the idea of focusing on customer experience end-to-end. Product and how it's delivered.
<TODO> Products are converging, the thing that makes you different is how it's delivered. 




<TODO> CFA discussion. You can get a chicken sandwich just about anywhere, but is now the 3rd largest fast food chain.
<TODO> Disney's product is magic, everyone is enabled to deliver it. No crying child policy, monorail pilots, custodial staff
<TODO> Culture change in your org, goes in "Onward" section at the end of the book.