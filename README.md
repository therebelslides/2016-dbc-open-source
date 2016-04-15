# Contributing to Open Source
*Trent Oswald, `trentoswald``@``therebelrobot.com`, @therebelrobot*

*Note: this is more useful after going through the slides, but feel free to poke around ;)*

## Start Your Own

- [ ] Release Code - Github, Gitlab, Bitbucket, Wherever
- [ ] Public and Permissive License
  - [choosealicense.com](http://choosealicense.com)
  - [tldrlegal.com](http://tldrlegal.com)
- [ ] Clear Documentation
  - [OSS Manifesto](http://ossmanifesto.org/)
  - [doc-squad](http://c4sf.me/docsquad)
- [ ] Testing
  - Unit (Tap, Tape, Ava, Mocha)
  - End to End (Nightwatch, Browserstack, Intern.io)
- [ ] Publish
  - NPM
- [ ] Evangelize - Reddit, Github, HackerNews

## Contribute to Others

- [ ] [up-for-grabs.net](http://up-for-grabs.net)
- [ ] Read `CONTRIBUTING` doc
- [ ] See where there are needs
  - Docs
  - Tests
  - Triage & replicate
  - Add fixes
  - Add features

## Additional Readings

[Branching model](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow) vs [Forking model](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow)

[code slide plugin](https://github.com/thejameskyle/spectacle-code-slide)

## Slide content

```js
function Contributing_to (openSource) {
  // Trent Oswald
  //    @therebelrobot
  //    therebelrobot.com
  // Dev Bootcamp, April 16th 2016

  what_is(openSource);

  (openSource !== freeSoftware);

  openSource = "source code available to the general public with relaxed or non-existent copyright restrictions";

  openSource = [
    "Rich and Thriving Community",
    "Shared Values",
    "Open Governance",
    "Ability and Freedom to Iterate",
    "Passion for Innovation"
  ]

  openSource << FreeSoftwareFoundation(1997)

  openSourceInitiative(1998)

  Netscape() // Now Mozilla Firefox
  Debian()
  LinuxKernel()

  openSource = [
    "Media Content", // Wikimedia Foundation
    "Hardware", // Raspberry Pi, Arduino
    "Beverages",// Open Source Cola, Brewtopia
    "Firearms", // 3D Printed firearms
    "Medicine", // Tropical Disease Initiative
    "Religion" // Open Siddur Project, Open Source Yoga Unity
  ]

  var whatMakesOpenSource = function () {
    releaseOfSourceCode()
            // Github, Gitlab, Bitbucket, etc
    publicAndPermissiveLicense()
            // MIT, ISC, GPLv3, Apache, etc
    clearDocumentation()
            // README, CONTRIBUTING, CHANGELOG
  }

  React // Facebook
  RubyOnRails // David Hansson
  Linux // The Linux Foundation
  Android // Google
  .NETframework // C# - Microsoft

  var howDoIOpenSource = function () {
    methods = [
      "Start Your Own",
      "Contribute to Others"
    ]

    if(method === "Start Your Own"){
      releaseOfSourceCode()
      publicAndPermissiveLicense()
          // choosealicense.com, tldrlegal.com
      clearDocumentation()
         // ossmanifesto.org, c4sf.me/docsquad

      testing() // Tap, Mocha, Nightwatch
      publishing() // NPM, Gems, LuaRocks
      evangelizing()
           // Github, HackerNews, Reddit, IRC

      if(broken) {
        buildFix()
        release
      }

      url("http://ossmanifesto.org")
      values = [
        "Respect",
        "Collaboration",
        "Healthy Debates",
        "Basic Documentation",
        "Consistent Versioning of releases"
      ]

    }
    if(method === "Contribute to Others") {
      humanInteraction()

      remember(`They\'re coders,
                 just like you`)
      remember(`Nobody is born a coder.
                 We all start somewhere.`)
      remember(`If you don\'t like a community,
                 find (or build) a new one`)

      contributionModels = [
        "Branching",
           // internal parallel code bases
        "Forking"
           // external parallel code base
      ]
      openSourceContributions === "Forking"

      CONTRIBUTING.md()
        // How to file an issue
        // What to include
        // How to contribute code

      GithubIssues = [
        "Ask for LICENSE (if none provided)",
        "Report found bugs",
        "Try to replicate logged bugs",
        "Suggest feature additions"
      ]
      remember(`Language / culture /
                   personality barriers`)
      remember(`Response times vary
                   dramatically`)

      GithubForking = [
        "Assist in documentation improvement",
        "Assist in writing tests",
        "Try fixing a currently reported bug",
        "Try fixing a bug you found",
        "Try adding a proposed feature",
        "Try adding a feature you would like"
        // WARNING: It is best practice
        //          to check in with
        //          a core contributor before
        //          adding features.
      ]

      url("http://up-for-grabs.net")
    }
  }
}
```
