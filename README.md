# To use these snippets
1. Clone this git repository to be in the directory: "C:\Users\<Your-Username>\Documents\Visual Studio 2022\Code Snippets\Visual C#\My Code Snippets"
2. In Visual Studio, inside of your test class, type out the name of the snippet (for example, type "fact" excluding quotes), and press tab twice to insert the code snippet
3. In the case of the "fact" snippet, your cursor will start at "MethodName" and let you replace it with your own method name.
4. Press "Tab" key after finishing your method name and your cursor will go to the "Scenario" section to be replaced. Repeat again for "ExpectedBehavior".
5. Finally, your cursor will be brought to below `// arrange` so you can start writing your test

## Snippets

`fact`: Xunit Fact for synchronous tests

``` csharp
[Fact]
public void MethodName_Scenario_ExpectedBehavior()
{
	// arrange

	// act


	// assert

}
```

`afact`: Xunit Fact for async tests

``` csharp
[Fact]
public async Task MethodName_Scenario_ExpectedBehavior()
{
	// arrange

	// act


	// assert

}
```
