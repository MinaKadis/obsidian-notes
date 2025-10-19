

Use `[DebuggerDisplay]` You add this attribute on top of the class to control how you want to display class info while debugging. 

## Example
```C#
[DebuggerDisplay("Order {OrderNumber}: {CustomerName} - {TotalAmount}")]
public Class Order{
	public Guid Id {get; private set;}
	public string OrderNumber {get; set;}
	public string CustomerName {get; set;}
	public decimal TotalAmount {get; set;}
	public OrderStatus Status {get; set;}
	public DateTime CreatedAt {get; set;}
}
});
