Write a simple dropdown component:
- receives a list of strings as a prop
- when clicked, those strings are shown as a dropdown list
- when an item in the list is clicked, the dropdown is closed and that item is shown as the selected item
- should also receive an "onSelected" prop, which is a function that will be called when a selection is made

```
<SimpleDropdown
	options={['apple', 'banana', 'orange']}
	onSelect={(item) => console.log('selected item:', item)}
/>
```

https://imgur.com/a/jBoWwFM

