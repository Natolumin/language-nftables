## 0.2.2
*   Variable definitions
*   Chain policies
    ```nftables
    chain input {
      type filter hook input priority 0
      policy drop
    }
    ```
*   Set flags
    ```nftables
    set filter blackhole{
      type ipv6_addr
      flags interval
      elements={::/96}
    }
*   A couple of bugfixes


## 0.2.1
*   Updated snippets
*   Concatenations
*   Includes

## 0.2.0 - First Release
*   Added most of table/chain/rule/set definitions
