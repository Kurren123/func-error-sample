To reproduce the error:
- Install azure functions core tools (mine is v4.0.4590)
- Run `func start` at the root folder. It should work.
- Open the fsproj file, uncomment the line `<!-- <PackageReference Include="Microsoft.Azure.WebJobs.Extensions.DurableTask" Version="2.7.2" /> -->`
- Run `func start` again, it should fail
