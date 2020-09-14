# 100 Days Of Code - Journal

### Day 1: September 6, 2020

**Today's Progress**: Finally got around to start this! As part of the daily challenge obligations, did a quick round of Java interview questions to freshen up memory (and just get started on something).

**Thoughts:** Starting the 100 days of code challenge 🎉 Or really, just a way to get to code more consistently, and organize my learning. Planning to dive in into my main language and platform of choice (Java and Spring), continue on frontend, and who knows what else—only impromptu browsing can tell!

### Day 2: September 12, 2020

**Today's Progress**: Resumed working on a small personal project again. Adding unit tests with testcontainers which I'm using for the first time, and which is why I wanted to do some testing with that library.

**Thoughts:** Took a bit of a break from the 100 days routine. I guess, personally, the most important part is just doing it, at whatever pace when life happens. As for the coding part of thoughts of the day, so far enjoying running tests with testcontainers; makes testing with postgres much easier.

### Day 3: September 13, 2020

**Today's Progress**: Adding some light new features, such as dictionaries API, and unit tests. Looked into adding some validation using `javax.validation` API; however for now, the project doesn't seem to benefit from it, as validations already in place are not checking simple singular fields. Which got me thinking of factoring out validation logic, as it really seem to blur with the rest of the service application code (which I'll look into more later, and maybe the Java validation library will still be of use).

**Thoughts:** I find that aside from the obvious puprose of testing to ensure correctness and expected output of code, it also gives a sense of security and certainty in knowing that changes and new additions are at least being monitored by an additional pair of eyes, figuratively speaking. So it's a good way not to just add checks and balances, but also add more confidence in your work. Also, I find writing tests is also a nice change of things, like shifting more focus to the what, and thus to what overall goals you as a programmer, and your program, are aiming to achieve. 

### Day 4: September 14, 2020

**Today's Progress**: Once upon a time, I took a closer look, and discovered that I did have use for the validation thing in my little project, so I added that, along with custom error handling for when `@Valid` throws errors. which apparently (and of course) one can override, repackage the whole thing, and send it even further, all the way to the moon.

**Thoughts:** Validation is neat. Also, digging around Spring API is never not entertaining. 10/10 would recommend. No seriously, diving under the hood of frameworks or libraries you use is perhaps one of the most powerful learning tools I have discovered so far in my life as a professional engineer. Not only it might give better understanding (and appreciation) for the kind of stuff those hidden apis are doing & how, but also can be a good starting ground in terms what to pay attention to, or what questions to ask, or just to read and try to understand other ppl's code. This isn't about Spring, but a much, much more general outlook at the resources at one's disposal as a developer, and something I can't recommend enough of.
