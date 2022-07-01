---
title: SMTP
slug: Glossary/SMTP
translation_of: Glossary/SMTP
---
<p><strong>SMTP</strong>（Simple Mail Transfer Protocol，简单邮件传输协议） 是用于发送的邮件的<a href="/zh-CN/docs/Glossary/Protocol">协议</a>。类似于<a href="/zh-CN/docs/Glossary/POP">POP3</a>和<a href="/zh-CN/docs/Glossary/NNTP">NNTP</a>，它是一个<a href="/zh-CN/docs/Glossary/State_machine">状态机</a>驱动的协议</p>

<p>该协议相对简单。最复杂的部分在于添加支持不同的验证机制（<a href="https://en.wikipedia.org/wiki/Generic_Security_Services_Application_Program_Interface"><abbr title="Generic Security Services Application Program Interface">GSSAPI</abbr></a>， <a href="https://en.wikipedia.org/wiki/CRAM-MD5"><abbr title="challenge-response authentication mechanism">CRAM-MD5</abbr></a>，<a href="https://en.wikipedia.org/wiki/NTLM"><abbr title="NT LAN Manager">NTLM</abbr></a>，MSN，AUTH LOGIN，AUTH PLAIN 等），处理错误响应以及在验证机制错误时进行状态回退（如服务器声明其支持某种机制但其实并不）。</p>

<h2 id="参见">参见</h2>

<ul>
 <li><a href="/zh-CN/docs/Glossary">术语表</a>

  <ul>
   <li><a href="/zh-CN/docs/Glossary/NNTP">NNTP</a></li>
   <li><a href="/zh-CN/docs/Glossary/POP">POP3</a></li>
   <li><a href="/zh-CN/docs/Glossary/Protocol">协议</a></li>
   <li><a href="/zh-CN/docs/Glossary/State_machine">状态机</a></li>
  </ul>
 </li>
 <li>维基百科
  <ul>
   <li>{{Interwiki("wikipedia", "SMTP")}}</li>
  </ul>
 </li>
</ul>