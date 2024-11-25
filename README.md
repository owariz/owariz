<h2 align="left">Hi 👋! I'm Variz</h2>

```csharp
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        var myProfile = new
        {
            Profile = new
            {
                Name = "Variz",
                Age = 19,
                Skills = new List<string> { "JavaScript/TypeScript", "Svelte", "React", "Vue", "Python", "Go", "MongoDB" }
            },
            Social = new
            {
                GitHub = "github.com/owariz",
                Discord = "v_variz",
                Email = "panitthapwon@gmail.com"
            }
        };

        Console.WriteLine("My Profile:");
        Console.WriteLine($"Name: {myProfile.Profile.Name}");
        Console.WriteLine($"Age: {myProfile.Profile.Age}");
        Console.WriteLine("Skills:");
        foreach (var skill in myProfile.Profile.Skills)
        {
            Console.WriteLine($"- {skill}");
        }
        Console.WriteLine("\nSocial Links:");
        Console.WriteLine($"GitHub: {myProfile.Social.GitHub}");
        Console.WriteLine($"Discord: {myProfile.Social.Discord}");
        Console.WriteLine($"Email: {myProfile.Social.Email}");
    }
}
```
###

<h2 align="left">📊 My Stats:</h2>

###

<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=owariz&hide_title=true&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=ayu-mirage&locale=en&hide_border=true&order=1" height="150" alt="stats graph"  />
  <img src="https://streak-stats.demolab.com?user=owariz&locale=en&mode=weekly&theme=ayu-mirage&hide_border=true&border_radius=5&order=3" height="150" alt="streak graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=owariz&locale=en&hide_title=true&layout=compact&card_width=320&langs_count=12&theme=ayu-mirage&hide_border=true&order=2" height="200" alt="languages graph"  />
  <br />
  <img src="https://fabianocouto-activity-graph.vercel.app/graph/?username=owariz&theme=tokyo-night&radius=6&area=true)" />
</div>
