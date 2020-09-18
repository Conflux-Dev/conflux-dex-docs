A market maker can easily interact with MatchFlow via <a href="../conflux-dex-api.html" target="_blank">REST API</a> and [WebSocket API](ws.md).

Firstly, please refer to the [document](reg_user.md) to add a new account in Conflux DEX. After that, market maker could call REST APIs to <a href="../conflux-dex-api.html#_place_order" target="_blank">place orders</a> or <a href="../conflux-dex-api.html#_cancel_order" target="_blank">cancel orders</a>. Unlike centralized exchanges, Conflux DEX requires EIP712 based user signature to place an order. Accordingly, market maker need to follow the [type schema](eip712.md) to sign place/cancel order request.