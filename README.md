# awesome-encoding-escaping

A repository for tools and documentation for learning string encoding & unicode escaping. An effective obfuscation method for writing offensive security testing payloads for web applications. 

Commonly used with programming languages like JavaScript, PHP, & HTML for WAF bypass. Encoding can also assist in your success as a red team operator when attempting to bypass file upload restrictions.

## Common encoding methods & examples

**HTML Encoding**
- The most basic and common form of encoding, in my opinion. You can find this used for URLs in your browser.

    **Example**:

    ASCII to HTML-encoded:

        ASCII - /
    
        HTML-encoded - %2F

    Pentest use case - Directory traversal:

        ASCII - ../../
    
        HTML-encoded - %2E%2E%2F%2E%2E%2F

## Resources

[CyberChef](https://gchq.github.io/CyberChef/) - A versatile web application used to obfuscate or deobfuscate strings. Can be ran offline and used for other scenarios as well. Includes various code beautifiers, decoders, and unescaping tools.

[Dencode](https://dencode.com/en/string) - An online string encoder/decoder. Quickly visualize various methods of encoding and unicode escaping inside the tool for a high-level overview.

[Dencode - Unicode Escape](https://dencode.com/en/string/unicode-escape) - An online unicode escaping tool, quickly visualize escaped payloads for character memorization or use.

[W3Schools - HTML URL Encoding Reference](https://www.w3schools.com/tags/ref_urlencode.ASP) - A reference for standard HTML URL encoding and their cooresponding ASCII character values.

[HTML URL Encoding - GeeksforGeeks](https://www.geeksforgeeks.org/html-url-encoding/) - An alternate reference for HRML URL encoding

[Gooogle Admin Toolbox - Encode/Decode](https://toolbox.googleapps.com/apps/encode_decode/) - Offers encoding and decoding for SAML, as well as a few code beautifiers. 

[OWASP XSS Filter Evasion Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/XSS_Filter_Evasion_Cheat_Sheet.html) - Contains working examples of encoded and escaped JavaScript payloads.

[Portswigger XSS Cheat Sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet) - Not directly encoding related, often need a bit of encoding or escaping for production use in the modern-day.
