# Hyper Text Markup Language
## What Is a Markup Language?
A markup language is a system for defining the structure, presentation, and/or purpose of content within a digital document so computer programs can interpret and display the content correctly.


* Markup languages encode text using specific vocabulary, symbols, and/or syntax rules.

* For example, the h1 tag in HTML (hypertext markup language) communicates that the enclosed text is a top-level heading.

* Search engines can use this information to better understand the subject matter of your page. While browsers can use this information to apply the relevant styling.
---
## type of Markup Language
**Semantic markup** (or descriptive markup) provides meaning to content by labeling that content’s structure and purpose. Which can help browsers, search engines, and developers interpret the content correctly.

* For example, in XML, <author>John Doe</author> identifies "John Doe" as the author of an article. But the markup doesn’t affect the presentation of this text.

**Presentational markup** controls the visual appearance of content so users see content in a specific way. This markup defines how the text should look without specifying how the system should render it.

* For example, in HTML, <b>Bold Text</b> marks the enclosed text as bold but doesn’t dictate the exact process the browser should use to achieve that appearance.

**Procedural markup** provides step-by-step commands for how content should be processed, formatted, or displayed. Instead of defining appearance, this markup directs the system on what to do with the text.

* For example, In LaTeX, \textbf{Bold Text} instructs the typesetting system to apply a bold font weight based on its backend processing rules.
---
# How does Web Works
## What is HTTP?
First things first, what is HTTP? HTTP is a TCP/IP-based application layer communication protocol that standardizes how clients and servers communicate with each other. It defines how content is requested and transmitted across the internet. By application layer protocol, I mean that it’s simply an abstraction layer that standardizes how hosts (clients and servers) communicate. HTTP itself depends on TCP/IP to get requests and responses between the client and server. By default, TCP port 80 is used, but other ports can also be used. HTTPS, however, uses port 443. 
Based on the uploaded images, here is the transcribed text, organized by the topics and versions of HTTP discussed:

### 1. HTTP/0.9 (1991)
* **Simple protocol**
* `GET` method only used
* $\rightarrow$ Request, Response

### 2. HTTP/1.0 (1996)
* Sending files plain text, HTML, Image file,
* `POST`, `HEAD`, `GET`
* request, response, status.
* But it does not support the
* Three ways handshaking.

### 3. HTTP/1.1 (1997)
* Added method (`PUT`, `OPTION`, `DELETE`)
* Pipelining used
* But **disadvantages**:
    * Chunks $\rightarrow$ 10 HTML, 5 stylesheet, 5 javascript. It
    * will be send separately, so it
    * will have **low latency**.
    * $\rightarrow$ We cannot able to achieve HTTP status. (Note: This point seems contradictory in the notes; usually, separate requests increase latency/overhead, and HTTP status codes are standard).

### 4. SPDY (2009)
* $\rightarrow$ Google
* $\rightarrow$ Introduced network
    * band width, latency
    * network Compression, network response
* But it does not rely on HTTP method, $\rightarrow$ It get grate compute they dropped SPDY but they inspired the idea to develop more HTTP/2

### 5. HTTP/2 (2015)
* $\rightarrow$ **low latency**
* $\rightarrow$ **Binary protocol**
* $\rightarrow$ **Multiplexing**
* $\rightarrow$ **Network security**
* $\rightarrow$ **Request prioritization**

---