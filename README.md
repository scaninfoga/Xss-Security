<h1 align="center">
  <br>
  <a href="https://github.com/scaninfoga/Xss-Security"><img src="http://scaninfoga.in/wp-content/uploads/2022/04/scaninfoga.png" alt="Xss-Security"></a>
  <br>
  Xss-Security
  <br>
</h1>



Xss-Security is a Cross Site Scripting detection suite equipped with four hand written parsers, an intelligent payload generator, a powerful fuzzing engine and an incredibly fast crawler.

Instead of injecting payloads and checking it works like all the other tools do, Xss-Security analyses the response with multiple parsers and then crafts payloads that are guaranteed to work by context analysis integrated with a fuzzing engine.
Here are some examples of the payloads generated by Xss-Security:
```
}]};(confirm)()//\
<A%0aONMouseOvER%0d=%0d[8].find(confirm)>z
</tiTlE/><a%0donpOintErentER%0d=%0d(prompt)``>z
</SCRiPT/><DETAILs/+/onpoINTERenTEr%0a=%0aa=prompt,a()//
```
Apart from that, Xss-Security has crawling, fuzzing, parameter discovery, WAF detection capabilities as well. It also scans for DOM XSS vulnerabilities.

### Main Features
- Reflected and DOM XSS scanning
- Multi-threaded crawling
- Context analysis
- Configurable core
- WAF detection & evasion
- Outdated JS lib scanning
- Intelligent payload generator
- Handmade HTML & JavaScript parser
- Powerful fuzzing engine
- Blind XSS support
- Highly researched work-flow
- Complete HTTP support
- Bruteforce payloads from a file
- Powered by [scaninfoga.in](https://scaninfoga.in), [Rohan](https://www.instagram.com/rohan_nahak.h.r/) and [Scaninfoga](https://www.scaninfoga.in/tools-software)
- Payload Encoding

### Documentation
- [Usage](https://github.com/scaninfoga/Xss-Security)



