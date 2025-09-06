---
permalink: /markdown/
title: "Resources"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---
# 本科生入学研读
## [[高质量大学怎么过？建议你看看《上海交通大学生存手册》]](https://survivesjtu.gitbook.io/survivesjtumanual/xu/xin-ban-xu-todo)
## [[大学开挂指南？]](http://ag-wang.github.io/files/university_student.pptx)

------------------------------------------------------------
# 研究生入学研读
## [[搞定科研思维：B站四讲]](https://www.bilibili.com/video/BV1be411977i/?spm_id_from=333.1007.tianma.1-2-2.click&vd_source=645b5d44d01b3611414e16a3216812a0)
## [[吴恩达教你：如何有效读论文？]](https://www.bilibili.com/video/BV17w41167rC/?spm_id_from=333.1007.tianma.4-1-11.click&vd_source=645b5d44d01b3611414e16a3216812a0)
## [[参考文献格式整理简介]](https://www.bilibili.com/video/BV1DC4y1r7qL/?vd_source=645b5d44d01b3611414e16a3216812a0)[[PDF]](http://ag-wang.github.io/files/reference_format_guide.pptx) 
## [[CCF推荐国际学术会议和期刊目录-2022年]][[PDF]](http://ag-wang.github.io/files/ccf_conf_journal_2022.pdf) 
## [[CCF推荐中文科技期刊目录-2019年]][[PDF]](http://ag-wang.github.io/files/ccf_chinese_journal_2019.pdf) 

---------------------------------------------------------
# 研究生写论文前研读
## TIPS on how to use ChatGPT to write an academic paper:
1. I'm now writing a research article about the role of pneumonectomy in N2 NSCLC. please help me with the writing. just answer yes.
2. Now write a structured abstract according to the following results, about 300 words, with background, methods, results, conclusions, and keywords.
3. Give me a good title/give me a title in the style of the annals of thoracic surgery.
4. Write the introduction part according to the abstract and the references I provided.
5.Now write a discussion part according to my results and the references I just provided.
6.Please summarize the abbreviations used in all the above paragraph l provided, listed them without numbers.
7. write the authors contribution, there are a total of five authors A,B,C,D,E and E is the corresponding author.
8. write the ethical statement, and the hospital is Shanghai Chest Hospital.
9. write a cover letter to the journal of NEJM.
10. suggest 5 suitable journals for my study, if about 5.


## Grammary Guidelines
1. The most common habits from more than 200 English papers written by Graduate Chinese Engineering Students.[[PDF]](http://ag-wang.github.io/files/The Most Common Habits from more than 200 English Papers.pdf) 

-------------------------------------------------------------

## Locations of key files/directories

* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

## Tips and hints

* Name a file ".md" to have it render in markdown, name it ".html" to render in HTML.
* Go to the [commit list](https://github.com/academicpages/academicpages.github.io/commits/master) (on your repo) to find the last version Github built with Jekyll. 
  * Green check: successful build
  * Orange circle: building
  * Red X: error
  * No icon: not built

## Resources
 * [Liquid syntax guide](https://shopify.github.io/liquid/tags/control-flow/)

## Markdown guide

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.

## Tables

### Table 1

| Entry            | Item   |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | 2016   | Description of the item in the list                          |
| [Jane Doe](#)    | 2019   | Description of the item in the list                          |
| [Doe Doe](#)     | 2022   | Description of the item in the list                          |

### Table 2

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com "Github").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.
