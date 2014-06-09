#### Usage:
    Just start new phpunit.xml with the following basic content:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<phpunit xmlns:xsi='http://www.w3.org/2001/XMLSchema-instance' xsi:noNamespaceSchemaLocation='phpunit.xsd'>
</phpunit>
```
and you will have autocomplete. This example assumes that phpunit.xsd is in the same directory as phpunit.xml. Change xsi:noNamespaceSchemaLocation if needed.

#### Notes:
    * PHPUnit allows for standalone <testsuite> element - this schema does not.
    * Based on 4.1.1 version
    * Instead of xsd:boolean, new Boolean type is defined as extension to xsd:string with two values 'true' and 'false' to allow autocompletion for boolean attributes.