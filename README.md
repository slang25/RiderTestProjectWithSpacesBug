### Rider Test Discovery Bug

Open the `RiderTestProjectWithSpacesBug.sln` solution with Rider (2025.2.1) and look at the test explorer, you will see Rider only discovers the test project with no spaces in, however `Test Project 2` is not discovered.
These test use TUnit, which using Microsoft Testing Platform.
