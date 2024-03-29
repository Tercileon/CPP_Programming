|[Table of Contents](/00-Table-of-Contents.md)|
|---|

---

## Resource Management

---

* **Resources:** files, heap allocated memory
* Resource-Allocation is Initialization \(**RAII**\)
* **Exceptions:** newer, cleaner, better ways to perform error handling
* **Copy and move:** l-values, r-values, move and copy constructors
* **Local Scope:** object lifecycle guarantees
* **Unique Pointers:** singular ownership
* **Shared Pointers:** shared ownership

---

### Resources

* Your program interacts with **resources**
* Must be **acquired** and later **released**
* Some examples include:
  * files
  * heap-allocated memory
  * network sockets
  * registry entries
  * mutex locks
* Your program must release these resources after it is done with them
* Failure to do so results in a **resource leak**, which is a bad thing
* Recall: **memory leaks** from C. 

---

|[Next Topic](/ch05_Resource_Management/5.01_resources.md)|
|---|
