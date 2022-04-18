In this homework we:

Let's add a field for Birthday. This field is optional, but there can be only one.
Let's add Birthday functionality to the Record class, namely the days_to_birthday function, which returns the number of days until the next birthday.
let's add the functionality of checking the correctness of the given values ​​for the fields Phone, Birthday.
Let's add pagination (pagination) for AddressBook for situations when the book is very large and you need to show the contents in parts, and not all at once. Let's implement this by creating an iterator over records.
Admission criteria:#
AddressBook implements an iterator method that returns a generator over AddressBook entries and returns a view for N entries in one iteration.
The Record class takes another additional (optional) argument of the Birthday class.
The Record class implements the days_to_birthday method, which returns the number of days until the contact's next birthday, if a birthday is given.
setter and getter logic for the value attributes of the Field descendants.
Validation of the entered phone number in the setter for value of the Phone class.
Validation of the entered birthday in the setter for value of the Birthday class.
