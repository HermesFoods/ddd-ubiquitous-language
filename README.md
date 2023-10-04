# ddd-ubiquitous-language

## Glossary 

**Client**: The person who will order the meal through the self-service totem.

**CPF**: The client's document identification.

**Product**: Meal information. Example: Hamburgers, French Fries, Soda, etc...

**Voucher**: The voucher allows to get a discount through a code in the self-service totem.

**Order**: Describes the list of products chosen by the client and the client's information.

**Order Sheet**: Describes the list of products chosen by the client and the client's information (from the kitchen's view).

**Invoice**: Describes the list of products chosen by the client and the client's information (from the client's view).

**Verification Code**: This verification code allows the client to get the meal in its final stage. PS: without this code, it's not possible to claim the meal with the attendant.

**Status**: Represents the order's actual status.

- **Paid:** The order's invoice payment has been accepted and successfully paid;
- **Canceled**: The order's invoice payment hasn't been accepted, so the order was canceled;
- **Received**: The order has been received by the cooks;
- **In Progress**: The order preparation has been started by the cooks;
- **Done**: The order is ready to be claimed by the client;
- **Finished**: The client has already claimed its meal.

**Meal**: The real representation of the order's items that are prepared by the cooks and claimed by the clients.
