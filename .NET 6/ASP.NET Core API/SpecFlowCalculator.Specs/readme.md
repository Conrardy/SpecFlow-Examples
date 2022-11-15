https://docs.specflow.org/projects/specflow-livingdoc/en/latest/LivingDocGenerator/Installing-the-command-line-tool.html
dotnet tool install --global SpecFlow.Plus.LivingDoc.CLI
livingdoc test-assembly .\bin\Debug\net6.0\SpecFlowCalculator.Specs.dll -t .\bin\Debug\net6.0\TestExecution.json