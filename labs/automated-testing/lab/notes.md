
```
    [Fact]
    public void SimpleIntegers_Bug17()
    {
        var service = new AdditionService();
        var expected = 19;
        var actual = service.Operate(2, 17);
        Assert.Equal(expected, actual);
    }
```