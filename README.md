# stack-exercise

Write a Stack class that represents a basic stack data structure. The Stack class should have the following methods:

Push: Pushes a new item onto the top of the stack.
Pop: Removes and returns the item at the top of the stack.
Peek: Returns the item at the top of the stack without removing it.
IsEmpty: Returns a boolean value indicating whether the stack is empty.
Then, write unit tests to ensure that all methods of the Stack class are working correctly. Your tests should cover a range of scenarios, including:

1. Testing for correct pushing of items onto the stack.
2. Testing for correct popping of items from the stack.
3. Testing for correct peeking of the item at the top of the stack.
4. Testing for correct identification of an empty stack.
5. Testing for correct handling of null and empty input values.

Here's a sample code structure to get you started:

```
public class Stack {
  // TODO: Implement stack data structure

  public void Push(object item) {
    // TODO: Implement push method
  }

  public object Pop() {
    // TODO: Implement pop method
  }

  public object Peek() {
    // TODO: Implement peek method
  }

  public bool IsEmpty() {
    // TODO: Implement isEmpty method
  }
}

[TestFixture]
public class StackTests {
  [Test]
  public void TestPush() {
    // TODO: Write test for push method
  }

  [Test]
  public void TestPop() {
    // TODO: Write test for pop method
  }

  [Test]
  public void TestPeek() {
    // TODO: Write test for peek method
  }

  [Test]
  public void TestIsEmpty() {
    // TODO: Write test for isEmpty method
  }
}
```

Your task is to complete the TODO comments with the appropriate code to implement the Stack class and its methods, and write the unit tests to verify their correctness. Good luck!
