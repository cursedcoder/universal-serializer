Universal Serializer
====================

Serialization without questions.

Examples:

```php
$serializer = new UniversalSerializer();
$input = $serializer->serialize([1, 'string', ['array']);
$output = $serializer->unserialize($input);
```
