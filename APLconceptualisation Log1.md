Basic Syntax and Structure

 
Alphabet Programming Language (APL) proposes an innovative approach where alphabetic symbols,
supplemented by numeric suffixes, are used to represent core programming functionalities.
The language is designed to be highly flexible, allowing multiple operations to be defined on a single line.

**Syntax Overview:**

 **Alphabetical Function Mapping**
Each letter is assigned a broad category, with specific functions differentiated by numbers.

 **A - Arithmetic Operations**
  `a1`: Addition (`a1 x y` adds `x` and `y`)
  `a2`: Subtraction (`a2 x y` subtracts `y` from `x`)
   `a3`: Multiplication (`a3 x y` multiplies `x` by `y`)
   `a4`: Division (`a4 x y` divides `x` by `y`)
  -`a5`: Modulus (`a5 x y` finds `x % y`)

 **B - Bitwise Operations**
   `b1`: AND (`b1 x y` performs `x & y`)
   `b2`: OR (`b2 x y` performs `x | y`)
   `b3`: XOR (`b3 x y` performs `x ^ y`)
   `b4`: NOT (`b4 x` performs `~x`)
  `b5`: Left Shift (`b5 x n` shifts `x` left by `n` bits)

 **C - Control Flow**
   `c1`: If (`c1 condition action` executes `action` if `condition` is true)
   `c2`: While (`c2 condition action` repeats `action` while `condition` is true)
   `c3`: For Loop (`c3 init condition update action` executes a for loop)
   `c4`: Break (`c4` exits a loop or block)
   `c5`: Continue (`c5` skips to the next iteration of a loop)

- **D - Data Handling**
   `d1`: Assignment (`d1 x y` assigns `y` to `x`)
   `d2`: Swap (`d2 x y` swaps the values of `x` and `y`)
  `d3`: Increment (`d3 x` increments `x` by 1)
   `d4`: Decrement (`d4 x` decrements `x` by 1)
   d5`: Array Access (`d5 arr i` accesses the `i`th element of `arr`)

**E - Input/Output**
  `e1`: Print (`e1 x` prints the value of `x`)
  `e2`: Input (`e2 x` takes input and stores it in `x`)
   `e3`: Read File (`e3 filename` reads data from a file)
   `e4`: Write File (`e4 filename data` writes `data` to a file)
   `e5`: Append File (`e5 filename data` appends `data` to a file)

**F - Functions and Procedures**
   `f1`: Define Function (`f1 name params body` defines a new function)
  `f2`: Call Function (`f2 name args` calls a function with arguments)
   `f3`: Return (`f3 value` returns a value from a function)
   `f4`: Lambda Function (`f4 params body` creates an anonymous function)
   `f5`: Recursion (`f5 name params` invokes a recursive function call)

**G - Logical Operations**
   `g1`: Greater Than (`g1 x y` checks if `x > y`)
   `g2`: Less Than (`g2 x y` checks if `x < y`)
   `g3`: Equal (`g3 x y` checks if `x == y`)
   `g4`: Not Equal (`g4 x y` checks if `x != y`)
   `g5`: Logical AND (`g5 x y` checks if both `x` and `y` are true)

**H - String Handling**
  `h1`: Concatenate (`h1 str1 str2` concatenates `str1` and `str2`)
   `h2`: Length (`h2 str` returns the length of `str`)
   `h3`: Substring (`h3 str start length` extracts a substring)
  `h4`: Find (`h4 str substr` finds `substr` in `str`)
   `h5`: Replace (`h5 str old new` replaces `old` with `new` in `str`)

 **I - Input/Output Expansion**
   `i1`: Open File (`i1 filename mode` opens a file in a specified mode)
   `i2`: Close File (`i2 file` closes an opened file)
   `i3`: Write Line (`i3 file data` writes a line of `data` to `file`)
   `i4`: Read Line (`i4 file` reads a line from `file`)
   `i5`: Seek File (`i5 file position` moves the file pointer)

 **J - JSON Operations**
   `j1`: Parse JSON (`j1 json_string` parses a JSON string into an object)
   `j2`: Stringify JSON (`j2 object` converts an object to a JSON string)
   `j3`: Access JSON (`j3 json key` accesses a value by `key` in JSON)
   `j4`: Modify JSON (`j4 json key value` modifies a JSON object)
   `j5`: Delete JSON Key (`j5 json key` deletes a key from a JSON object)

**K - Collections**
   `k1`: Create List (`k1` creates a new list)
   `k2`: Append to List (`k2 list item` appends `item` to `list`)
   `k3`: Remove from List (`k3 list item` removes `item` from `list`)
   `k4`: Get List Size (`k4 list` returns the size of `list`)
   `k5`: Sort List (`k5 list` sorts the list)

**L - Logging**
   `l1`: Log Info (`l1 message` logs an informational message)
   `l2`: Log Warning (`l2 message` logs a warning message)
   `l3`: Log Error (`l3 message` logs an error message)
   `l4`: Set Log Level (`l4 level` sets the log level)
   `l5`: Log Debug (`l5 message` logs a debug message)

**M - Mathematical Operations**
   `m1`: Sine (`m1 x` returns the sine of `x`)
   `m2`: Cosine (`m2 x` returns the cosine of `x`)
   `m3`: Tangent (`m3 x` returns the tangent of `x`)
   `m4`: Square Root (`m4 x` returns the square root of `x`)
   `m5`: Exponent (`m5 x y` returns `x` raised to the power of `y`)

**N - Network Operations**
   `n1`: Open Socket (`n1 host port` opens a network socket)
   `n2`: Send Data (`n2 socket data` sends data through `socket`)
   `n3`: Receive Data (`n3 socket` receives data from `socket`)
   `n4`: Close Socket (`n4 socket` closes the network socket)
   `n5`: Connect (`n5 socket host port` connects to a remote host)

**O - Object-Oriented Operations**
   `o1`: Define Class (`o1 name body` defines a new class)
   `o2`: Instantiate Object (`o2 class_name args` creates a new object)
   `o3`: Access Property (`o3 object property` accesses an object's property)
   `o4`: Modify Property (`o4 object property value` modifies an object's property)
   `o5`: Call Method (`o5 object method args` calls a method on an object)

**P - Performance Monitoring**
   `p1`: Start Timer (`p1` starts a performance timer)
   `p2`: Stop Timer (`p2` stops the performance timer)
   `p3`: Get Timer Value (`p3` returns the elapsed time)
   `p4`: Memory Usage (`p4` returns the current memory usage)
   `p5`: CPU Usage (`p5` returns the current CPU usage)

**Q - Queue Operations**
   `q1`: Create Queue (`q1` creates a new queue)
   `q2`: Enqueue (`q2 queue item` adds `item` to `queue`)
   `q3`: Dequeue (`q3 queue` removes and returns the front item from `queue`)
   `q4`: Peek Queue (`q4 queue` returns the front item without removing it)
   `q5`: Is Queue Empty (`q5 queue` checks if the queue is empty)

**R - Regular Expressions**
   `r1`: Match (`r1 pattern string` matches `pattern` in `string`)
   `r2`: Replace (`r2 pattern replacement string` replaces `pattern` in `string` with `

replacement`)
   `r3`: Split (`r3 pattern string` splits `string` by `pattern`)
   `r4`: Find All (`r4 pattern string` finds all matches of `pattern` in `string`)
   `r5`: Compile (`r5 pattern` compiles a regex pattern for reuse)

**S - System Operations**
   `s1`: Execute Command (`s1 command` executes a system command)
  `s2`: Get Environment Variable (`s2 var` returns the value of an environment variable)
   `s3`: Set Environment Variable (`s3 var value` sets an environment variable)
   `s4`: List Files (`s4 directory` lists files in a directory)
   `s5`: Change Directory (`s5 directory` changes the current directory)

**T - Time Operations**
   `t1`: Get Current Time (`t1` returns the current system time)
   `t2`: Sleep (`t2 seconds` pauses execution for a specified time)
   `t3`: Format Time (`t3 format time` formats `time` according to `format`)
   `t4`: Parse Time (`t4 format string` parses a time `string` according to `format`)
   `t5`: Stopwatch (`t5` starts or stops a stopwatch)

**U - Utility Functions**
   `u1`: Generate UUID (`u1` generates a unique identifier)
   `u2`: Base64 Encode (`u2 string` encodes `string` in Base64)
   `u3`: Base64 Decode (`u3 string` decodes `string` from Base64)
   `u4`: Hash (`u4 algorithm string` returns the hash of `string` using `algorithm`)
   `u5`: Validate Email (`u5 email` checks if `email` is valid)

**V - Variable Management**
   `v1`: Declare Variable (`v1 name` declares a new variable)
   `v2`: Initialize Variable (`v2 name value` initializes a variable with `value`)
   `v3`: Delete Variable (`v3 name` deletes a variable)
   `v4`: Check Existence (`v4 name` checks if a variable exists)
   `v5`: List Variables (`v5` lists all variables)

**W - Web Operations**
   `w1`: Send HTTP GET (`w1 url` sends an HTTP GET request to `url`)
   `w2`: Send HTTP POST (`w2 url data` sends an HTTP POST request with `data`)
   `w3`: Parse URL (`w3 url` parses `url` into components)
   `w4`: Download File (`w4 url destination` downloads a file from `url`)
   `w5`: Upload File (`w5 url file` uploads a `file` to `url`)

 **X - XML Operations**
   `x1`: Parse XML (`x1 xml_string` parses an XML string into an object)
   `x2`: Serialize XML (`x2 object` converts an object to an XML string)
   `x3`: Access XML Node (`x3 xml path` accesses a node in an XML document)
   `x4`: Modify XML Node (`x4 xml path value` modifies a node in an XML document)
   `x5`: Delete XML Node (`x5 xml path` deletes a node from an XML document)

**Y - YAML Operations**
   `y1`: Parse YAML (`y1 yaml_string` parses a YAML string into an object)
   `y2`: Serialize YAML (`y2 object` converts an object to a YAML string)
   `y3`: Access YAML Node (`y3 yaml path` accesses a node in a YAML document)
   `y4`: Modify YAML Node (`y4 yaml path value` modifies a node in a YAML document)
   `y5`: Delete YAML Node (`y5 yaml path` deletes a node from a YAML document)

- **Z - Zip Operations**
   `z1`: Compress (`z1 files archive` compresses `files` into `archive`)
   `z2`: Decompress (`z2 archive destination` decompresses `archive` to `destination`)
   `z3`: List Archive (`z3 archive` lists the contents of an `archive`)
   `z4`: Add to Archive (`z4 archive file` adds a `file` to an `archive`)
   `z5`: Extract File (`z5 archive file destination` extracts `file` from an `archive` to `destination`)

  Platform-Specific APIs

APL incorporates a symbolic approach to platform-specific APIs using a container symbol `0`, followed by a platform-specific symbol (e.g., `!`, `@`, `#`). 
This notation allows the definition of platform-specific operations, enabling the same codebase to interact with different operating systems.

**Platform Containers:**

`0!`: Windows API
 `0@`: Linux API
 `0#`: macOS API

**Example Usage:**

```plaintext
0!  # Windows API Container
a1 5 10  # Addition (5 + 10)
e1 "Hello from Windows!"  # Print

0@  # Linux API Container
a2 10 3  # Subtraction (10 - 3)
e1 "Hello from Linux!"  # Print

0#  # macOS API Container
a1 7 8  # Addition (7 + 8)
e1 "Hello from macOS!"  # Print
```

Code debbuging:
Different colors to different categories of symbols or functions are assign to make the code easier readble.
depending on the function. 
//Peoples have to choose on their own.  What colors will be implimented.

In addition to the Code Editor a addon should be added for online database of prewritten code assets.
With then allow to; APL enables users to leverage a vast repository of reusable code,
reducing the need for manual coding of common functionalities. This feature is symbolized by the `?!` notation, 
which triggers the asset retrieval system.
When this symbol is used in the code, 
it opens a pop-up window that displays available categories and options for prewritten code, 
helping users to quickly locate the exact functionality they need.

**Example**:
    ```plaintext
    ?! math addition
    ```

Users can browse through categories (e.g., Math, String Handling, File I/O) or use specific search terms/pins to locate assets
The selected asset can then be automatically inserted into the code, with the option to customize or modify it as needed.
Each asset is tagged with relevant terms or pins that describe its functionality, making it easy to locate via the search system.

Gravity is a command when invoked, temporarily splits and spaces out the code for easier reading and debugging. 
After one hour, the code automatically reverts to its original form. The word Gravity deletes automatically after the given Time. 
With the ^ symbol extends the Gravity effect by one additional hour.
Delete Gravity with reversing the word in between the command-line: ytivarG
This Method is specially constructed so you pay attention to you coding. 
Better do not make mistakes. 


Example for 5 Hours:
Gravity^^^^^
a1 5 10
a3 2 3
f1 
e1 
Gravity

Command:
Modulus
Is written first and last as a closer.
APL then uses the Quantum Libaries/backround-mathematical function/modification
to easy code.

Modulus
a1 5 10
a3 2 3
f1 
e1 
Modulus

Command
Photon
Does nothing for now. As Photonic CPUs are in prototype phase.

Understanding Line Breaks in APL
1. Single-Line Execution:
APL was designed so that all code could be written on a single line, meaning the entire program or function could be on one line without affecting its execution.
This allows for compact and continuous writing of code, where each statement is sequentially processed.
2. Line Breaks as Execution Barriers:
If a line break is introduced, it acts as a barrier, breaking the sequence of execution. This would mean the code on the next line wouldn't automatically continue from the previous line unless explicitly connected.
This could be used intentionally to separate code segments or make the code more readable.
