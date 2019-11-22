#Learning Redis

Using redis CLI

## Strings 

1- set <key> <value>

2- get <key>

3- del <key>

// More coming up 

## Lists (linked lists structure)

1- RPUSH <list-name> <item> //Push an item from the right side

2- LPUSH <list-name> <item> // push an item from the left

3- RPOP  <list-name> // simialr to pop from a stack 

4- LPOP  <list-name> // simialr to dequeueing

5- LRANGE <list-name> <start> <end>

6- LINDEX <list-name> <index> // Fetches an item at a given position in the list

To range over the entire list 
`LRANGE <list-name> 0 -1`

// More coming up
  
## Sets (hash table with no duplication allowed. Unordered)

1- SADD <set-name> <value>

2- SMEMBERS <set-name> // Returns all members of the set - might be slow for large data sets

3- SREM <set-name> <value> // Remove an item from set if exists

// More coming up 

## Hashes (Stores key value pairs)

1- HSET <hashtable-name> <key> <value> // Set a key valu-pair to a hash table 

2- HGET <hashtable-name> <key> // Retrive the value of a key 

3- HGETALL <hashtable-name> // Retirve the entire hashtable 

4- HDEL Remove a key from the hash if it exist 

// More coming up 

## ZSET (sorted list)
1- ZADD <zsorte-name> <key (numeric)> <value>

2- ZRANGE <zsorted-name> <key> <value>

3- ZRANGEBYSCORE <zsorted-name> <key> <value>

4- ZREM <zsorted-name> <key>

// More coming up




