**My Messy Post-It Notes**

- These are my real post-it notes around my desk. 
- They are as un-ordered lists.
- They have no logical hierarchy.
- They might be wrong, misunderstood, confusing :/
- They seem chaotic, may be they are so :) 
- They are public because anybody would want to correct me …
- Thank you :)

> start

---
**SaaS, PaaS, IaaS**

    IaaS = Infrastructure as a Service
    PaaS = Platform as a Service
    SaaS = Software as a Service
    
    SaaS
        - Apllication data
        - Data
        - Runtime
        - OS
        
        IaaS & PaaS
            - Servers
            - Load Balancers
            - File Storage
            - Networking
**Note:** _SaaS_ includes _IaaS_ and _PaaS_

---

**Pascal Pyramid**

if n is row order and k is the number order from left than n*th* rows k*th* number is = n!/ (k!*(n-k)!)

     1.     1
     2.    1 1
     3.   1 2 1
     4.  1 3 3 1
     .
     .
     .
     n. 1... k ...1
The number at the n*th* row and k*th* order is ``= n!/ (k!*(n-k)!)``

---

**4 Horseman of Javascript Interview**

- Basic to Advanced Javascript Knowledge and Concepts
- Interview Questions: Algorithms, Data Structures, Big-O-Notation, Problem Solving, Recursion, Dynamic Programming etc.
- Frameworks, Tools, ServerSide, ClientSide, NoSQL etc.
- 


---
**Event Bubbling (EB) & Event Delegation (ED)** 

ED is bubbling up in the DOM tree hierarchy. From inside out, from the source trigger element to Window object.

ED is spreading from trigger element into all child elements.

---
**Convert Map to Array**

``= Array.from(myMap)``

 
**Convert Array to Map**

``= new Map(myArray) `` 

_If array is a 2D key-value type array._

> For example: ``[[key1,val1],[key2,val2],[key3,val3]]``)
    
---
    const object = {x:42, y:50}
    const entries = Object.entries(object);
    // [['x',42],['y',50]]
    
    const result = Object.fromEntries(entries);
    // {x:42, y:50}
 
   
---
**Learn these like your hand**
- String Methods !
- Array Methods !
- Object Methods !
> some  of interview questions easly handle with these three of javascript method families

---

**Ports we Love**

    20  FTP-data (TCP)
    21  FTP (TCP)
    115 SFTP (Secure FTP)
    989 FTP over SSL (TCP)
    990 FTP over SSL (TCP)
    22  SSH (TCP)
    23  TelNet (TCP)
    992 TelNets (TelNet over SSL)
    3389 RDP (Remote Desktop Protocol)
    39  RLP (Resource Location Protocol)
    
    25  SMTP (TCP)
    110 POP3 (TCP)
    995 POP3S (POP3 Secure)
    143 IMAP (TCP)
    993 IMAPS (IMAP Secure)
    
    53  DNS (TCP/UDP)
    
    63  WhoIs Service
    565 WhoAmI (who am i user id listing)
    
    67  DHCP (UDP) 
    68  DHCP (UDP)   
    
    79  Finger
    
    80  HTTP (TCP)
    443 HTTPS (TCP)
    
    113 Auth (Authentication and Ident Protocol)
    
    123 NTP (Network Time Protocol)
    194 IRC (Internet Relay Chat)
    994 IRCS (IRC Secure)
    
    
     
all TCP/UDP ports : https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers

---
**NodeJS**
- Express
    - Express Generator
- View Engines
    - EJS
    - Handlebars
    - Hogan.js
    - Pug (Jade)
    - Twig
    - Vash
- Style Sheet Engines
    - Stylus
    - LESS
    - Compass
    - SASS
- ORM
    - Sequelize
    - Mongoose
    -      
---
**JS Subjects**
- Currying
- Partial Application
- High Order Functions
- IIFE
- Mutable vs Immutable
- Closure
- Scope
- .apply(), .bind(), .call()

---
**Function.prototype**

- Properties
    - caller
    - length
    - prototype
    - prototype.name
- Methods
    - .apply()
    - .bind()
    - .call()
    - .toSource()
    - .toString()    

---
- ``parent.replaceChild(new,old)``
- ``document.addEventListener('load',callback)`` yerine
- ``document.addEventListener('DOMContentLoaded',callback)`` kullanilabilir. Fark: ``load`` her seyin yuklenmesini bekler, ``DOMContentLoaded`` image,css, subframe beklemez, html yuklendi ve render edildiyse calisir.

---
**Browser Extensions**
- Content page (DOM side) included in page sources. And runs from there
- Event page (background) + PopUp works with APIs.
- These two groups communicate via ``messages``.
---










