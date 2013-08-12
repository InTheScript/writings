NuGet developer: Help me help you
=================================

Are you a developing NuGet packages? Good. Me too. We developers all make mistakes from time to time. And the problem is, some of those mistakes become vulnerabilities. Now the problem is, how will the users of your library know?  

Using libraries with known vulnerabilities is a big problem. So big that it has in fact made it to the newly published [OWASP Top 10 2013](https://www.owasp.org/index.php/Top_10#OWASP_Top_10_for_2013). It's under *A9 Using Known Vulnerable Components*.

How can you help?
-----------------
Help me help you, or rather help me help your package's users. I have created a NuGet pacakge called [SafeNuGet](https://github.com/eoftedal/SafeNuGet). After installing this package into a project, SafeNuGet will check the status of the references libraries on every build, and warn the developers if anything is found to be vulnerable. However the status of the libraries need to be maintained. This is wher you come in. We help the users of our libraries by maintaining a [a list of vulnerable versions of our packages](https://github.com/eoftedal/SafeNuGet/blob/master/feed/unsafepackages.xml). And in the true spirit of Open Source, everything is free.

So how do you submit your list of vulnerable versions? You can either [register an issue](https://github.com/eoftedal/SafeNuGet/issues), create a [pull request](https://github.com/eoftedal/SafeNuGet) or send me an email at [erlend@oftedal.no](mailto:erlend@oftedal.no). Please include the package id, the versions affected and a URL for more information.

Thank you for helping out.

Code contributions
-------------------
If you want to help improve SafeNuGet itself as well, you are more than welcome to. Pull requests are more than welcome, and so are suggested enhancements through github's issue tracker.

Like the idea?
--------------
Help me spread the word, by telling your fellow NuGetters.

