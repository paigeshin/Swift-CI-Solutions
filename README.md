# Swift-CI-Solutions

# The most common options for CI solutions

## These are the most commonly used solutions for running a CI server that’s used for Swift projects today:

- Travis CI, which is a cloud-based solution that gives you a VM to build your code in. You pick your environment and then you run your build commands using tools like xcodebuild, swift build, or fastlane. It’s free for open source projects, and there’s also several paid tiers for closed source ones.

- Circle CI, very similar to Travis in that they also offer a cloud-based VM for you to build in, and give you access to a command line where you can run your build tools. However, it’s not free for open source projects (unless you’re only building on Linux) — but they do offer a 2 week free trial.

- Bitrise, which takes a slightly different approach than both Travis and Circle, in that they also offer a web-based UI to set up CI pipelines, as well as automated setups when adding a new project. Bitrise is free for both open source projects and private ones, as long as they take less than 10 minutes to build.

- Jenkins, if you’re the kind of person who likes to build things yourself (no shame in that, it can make for an interesting weekend project 😀), Jenkins is usually the way to go. It’s basically a package you install on your own hardware (typically a Mac Mini in someone’s closet), which gives you a CI server you can configure to your heart’s content.

- Xcode Server/Bots is Apple’s official way to do CI for Swift & Objective-C projects. It does provide some sweet integration with Xcode, and has a very nice UI, but I’ve yet to hear anyone deploy it successfully on any significantly complex project 😅 Please let me know if you’ve heard otherwise though! 👍
