---
title: "HTML Entities: A Complete Reference Guide"
description: "Learn about HTML entities, when to use them, and a reference table of common characters."
publishDate: "2026-02-04"
category: "Development"
tags: ["html", "entities", "web"]
image: "https://images.pexels.com/photos/270488/pexels-photo-270488.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
imageAlt: "Close-up of HTML code lines highlighting web development concepts and techniques."
faq:
  - q: "What should I know about html entities reference?"
    a: "This guide covers the essentials of html entities reference with practical examples. Use our free text tools at freetoolkit.cc for instant calculations and conversions."
  - q: "Are there free tools for this?"
    a: "Yes! Visit text.freetoolkit.cc for free online tools. No sign-up, no download — just enter your data and get instant results."
  - q: "How often is this guide updated?"
    a: "We regularly update our guides with the latest information and best practices. Bookmark this page for the most current text recommendations."
---

<div style="margin: 2rem 0; background: #1e293b; border-radius: 12px; padding: 1.2rem; border: 1px solid #334155;"><div style="font-weight: 700; font-size: 0.85rem; color: #94a3b8; margin-bottom: 0.8rem;">Common HTML Entities</div><div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 0.4rem; font-size: 0.75rem;"><div style="background: #334155; padding: 0.4rem; border-radius: 6px; text-align: center;"><span style="color: #60a5fa; font-family: monospace;">&amp;amp;</span> <span style="color: #94a3b8;">→ &</span></div><div style="background: #334155; padding: 0.4rem; border-radius: 6px; text-align: center;"><span style="color: #60a5fa; font-family: monospace;">&amp;lt;</span> <span style="color: #94a3b8;">→ &lt;</span></div><div style="background: #334155; padding: 0.4rem; border-radius: 6px; text-align: center;"><span style="color: #60a5fa; font-family: monospace;">&amp;gt;</span> <span style="color: #94a3b8;">→ &gt;</span></div><div style="background: #334155; padding: 0.4rem; border-radius: 6px; text-align: center;"><span style="color: #60a5fa; font-family: monospace;">&amp;quot;</span> <span style="color: #94a3b8;">→ "</span></div><div style="background: #334155; padding: 0.4rem; border-radius: 6px; text-align: center;"><span style="color: #60a5fa; font-family: monospace;">&amp;nbsp;</span> <span style="color: #94a3b8;">→ (space)</span></div><div style="background: #334155; padding: 0.4rem; border-radius: 6px; text-align: center;"><span style="color: #60a5fa; font-family: monospace;">&amp;copy;</span> <span style="color: #94a3b8;">→ ©</span></div></div></div>
HTML entities are special codes used to display reserved characters and symbols in web pages. Understanding HTML entities is essential for web developers and content creators.

## Why HTML Entities Exist

Certain characters have special meaning in HTML. The < and > characters define HTML tags, the & character starts entity references, and quotation marks define attribute values. To display these characters as text rather than code, you must use HTML entities.

## Entity Syntax

HTML entities can be written in two ways:
- Named entities: &name; (e.g., &amp; for &)
- Numeric entities: &#number; (e.g., &#38; for &)
- Hex entities: &#xhex; (e.g., &#x26; for &)

## Essential HTML Entities

| Character | Named | Numeric | Description |
|---|---|---|---|
| & | &amp; | &#38; | Ampersand |
| < | &lt; | &#60; | Less than |
| > | &gt; | &#62; | Greater than |
| " | &quot; | &#34; | Double quote |
| ' | &apos; | &#39; | Single quote |
| © | &copy; | &#169; | Copyright |
| ® | &reg; | &#174; | Registered |
| ™ | &trade; | &#8482; | Trademark |
| — | &mdash; | &#8212; | Em dash |
| – | &ndash; | &#8211; | En dash |
| • | &bull; | &#8226; | Bullet |
|   | &nbsp; | &#160; | Non-breaking space |

## When to Use HTML Entities

1. Displaying reserved characters (< > & " ')
2. Inserting special symbols not on your keyboard
3. Ensuring correct display across different browsers and encodings
4. Preventing XSS (cross-site scripting) attacks by encoding user input

Use our HTML Encoder/Decoder tool to quickly convert between raw text and HTML entities.