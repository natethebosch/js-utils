
# Event utils

## Canceler
Supports other classes that allow for cancelable asynchronous operations

## EventEmitter
| Name | Description |
| - | - |
| Listen(callback) | returns { remove: function() } |
| Emit(obj) | calls each registered callback |
| ListenerCount() | int |

## Fetchable

Has a nice way of organizing retrievable data. Uses a Cacheable to store it's data value

| Name | Description |
| - | - |
| .fetching | bool store state for asynchronous fetch |
| .hasMore | bool for list operations |
| get() | |
| set(obj, expiry_ms) | |
| invalidate() | |

## IntervalUntilTrue

Does calls the callback at a specified interval until the callback returns true.