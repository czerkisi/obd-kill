# Device Configuration

### 5. Device Configuration

### 5.1. Internal momentary pushbutton switches

\------

### 5.2. Update firmware&#x20;

\------

### 5.3. Hardware Setup&#x20;

\------

### 5.4. CAN Setup&#x20;

\------

### 5.6. MISC IO Setup&#x20;

\------

### 5.7. Multithreading Setup
The Raspberry Pico built into the OBD-Kill has two cores which allows it to perform multithreaded executions. \_thead is a library built into MicroPython that provides low-level primitives for working with multiple threads. If you try to use more than two threads, your Raspberry Pico will throw an OSError
