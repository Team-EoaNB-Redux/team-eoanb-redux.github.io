---
title: Release Process
# Not listed in ToC, but linked via /dev/contributing/
---
1. Update the version strings in Java files to the next release version as illustrated in [this commit](https://github.com/libgdx/libgdx/commit/237c023d1d4844144bf384e9e1ec9fccdbf961b8).
2. Create a [new release on GitHub](https://github.com/libgdx/libgdx/releases).
3. A new GitHub "Build and publish" workflow build with event "release" will be started that builds and publishes everything to Sonatype and AWS. Wait for the build to finish.
4. Log into http://oss.sonatype.com (ask Mario for username:password) and do what's described [here](https://central.sonatype.org/publish/publish-guide/#SonatypeOSSMavenRepositoryUsageGuide-8a.ReleaseIt).
   
   The credentials for Sonatype are available from Mario Zechner (badlogicgames@gmail.com).
   {: .notice--info}

Afterwards, a new changelog post needs to be created. Check out [this](https://github.com/libgdx/libgdx.github.io/wiki/Posts#changelogs) page for more info!
