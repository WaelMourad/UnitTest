   What is Unit Test ?
   A unit test is a function that tests a unit of work.

	• Unit Test Frameworks:
		○ MSTest
		○ MbUnit
		○ Nunit
		○ xUnit
	
	• [AAA Pattern] is a common way of writing unit tests.
		○ Arrange: Initialize objects that will be passed to the method which being tested.
		○ Act: Invoke the method which being tested.
		○ Assert: Verifies that the method being tested behaves as expected.
	
	• Benefits of unit tests:
		○ Find bugs early which saves development time
		○ Significantly reduce production bugs
		○ Unit tests make complex code easy to understand
		○ Provide some sort of documentation of code for developers
		○ Easier to change and refactor code
		○ Developers became confident
		
	• Unit Test Naming Convention:
		○ Method: [UnitOfWork_StateUnderTest_ExpetedBehaviour]
			  [ActualMethodName_ParametersGiven_ExpectedResult]
			       
		○ Class:  [ClassNameTest]
