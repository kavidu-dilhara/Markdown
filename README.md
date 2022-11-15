# Introduction


<!DOCTYPE html>
<html lang="en">
  <head>
  

</head>

  <body data-spy="scroll" data-target="#toc">

<h2>Learn Markdown </h2> 
<a href="https://kavidu-dilhara.gitbook.io/learn-markdown/"><img src="https://pronunciationapp.com/wp-content/uploads/2020/02/click-here-button-gif-1-1.gif"></a>

 <h2 id="what-is-markdown">What is Markdown?</h2>

<p>Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by <a href="https://daringfireball.net/projects/markdown/">John Gruber</a> in 2004, Markdown is now one of the world’s most popular markup languages.</p>

<p>Using Markdown is different than using a <a href="https://en.wikipedia.org/wiki/WYSIWYG">WYSIWYG</a> editor. In an application like Microsoft Word, you click buttons to format words and phrases, and the changes are visible immediately. Markdown isn’t like that. When you create a Markdown-formatted file, you add Markdown syntax to the text to indicate which words and phrases should look different.</p>

<p>For example, to denote a heading, you add a number sign before it (e.g., <code class="language-plaintext highlighter-rouge"># Heading One</code>). Or to make a phrase bold, you add two asterisks before and after it (e.g., <code class="language-plaintext highlighter-rouge">**this text is bold**</code>). It may take a while to get used to seeing Markdown syntax in your text, especially if you’re accustomed to WYSIWYG applications. The screenshot below shows a Markdown file displayed in the <a href="/tools/vscode/">Visual Studio Code text editor</a>.</p>

<p><img srcset="https://mdg.imgix.net/assets/images/vscode.png?auto=format&amp;fit=clip&amp;w=480 480w,              https://mdg.imgix.net/assets/images/vscode.png?auto=format&amp;fit=clip&amp;q=40&amp;w=1080 1080w" src="https://mdg.imgix.net/assets/images/vscode.png" class="img-fluid" alt="Markdown file in the Visual Studio Code text editor" sizes="100vw" /></p>

<p>You can add Markdown formatting elements to a plaintext file using a text editor application. Or you can use one of the many Markdown applications for macOS, Windows, Linux, iOS, and Android operating systems. There are also several web-based applications specifically designed for writing in Markdown.</p>

<p>Depending on the application you use, you may not be able to preview the formatted document in real time. But that’s okay. <a href="https://daringfireball.net/projects/markdown/">According to Gruber</a>, Markdown syntax is designed to be readable and unobtrusive, so the text in Markdown files can be read even if it isn’t rendered.</p>

<blockquote>
  <p>The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions.</p>
</blockquote>

<h2 id="why-use-markdown">Why Use Markdown?</h2>

<p>You might be wondering why people use Markdown instead of a WYSIWYG editor. Why write with Markdown when you can press buttons in an interface to format your text? As it turns out, there are several reasons why people use Markdown instead of WYSIWYG editors.</p>

<ul>
  <li>
    <p>Markdown can be used for everything. People use it to create <a href="#websites">websites</a>, <a href="#documents">documents</a>, <a href="#notes">notes</a>, <a href="#books">books</a>, <a href="#presentations">presentations</a>, <a href="#email">email messages</a>, and <a href="#documentation">technical documentation</a>.</p>
  </li>
  <li>
    <p>Markdown is portable. Files containing Markdown-formatted text can be opened using virtually any application. If you decide you don’t like the Markdown application you’re currently using, you can import your Markdown files into another Markdown application. That’s in stark contrast to word processing applications like Microsoft Word that lock your content into a proprietary file format.</p>
  </li>
  <li>
    <p>Markdown is platform independent. You can create Markdown-formatted text on any device running any operating system.</p>
  </li>
  <li>
    <p>Markdown is future proof. Even if the application you’re using stops working at some point in the future, you’ll still be able to read your Markdown-formatted text using a text editing application. This is an important consideration when it comes to books, university theses, and other milestone documents that need to be preserved indefinitely.</p>
  </li>
  <li>
    <p>Markdown is everywhere. Websites like <a href="/tools/reddit/">Reddit</a> and GitHub support Markdown, and lots of desktop and web-based applications support it.</p>
  </li>
</ul>

<h2 id="kicking-the-tires">Kicking the Tires</h2>

<p>The best way to get started with Markdown is to use it. That’s easier than ever before thanks to a variety of free tools.</p>

<p>You don’t even need to download anything. There are several online Markdown editors that you can use to try writing in Markdown. <a href="https://dillinger.io/">Dillinger</a> is one of the best online Markdown editors. Just open the site and start typing in the left pane. A preview of the rendered document appears in the right pane.</p>

<p><img srcset="https://mdg.imgix.net/assets/images/dillinger.png?auto=format&amp;fit=clip&amp;w=480 480w,              https://mdg.imgix.net/assets/images/dillinger.png?auto=format&amp;fit=clip&amp;q=40&amp;w=1080 1080w" src="https://mdg.imgix.net/assets/images/dillinger.png" class="img-fluid" alt="Dillinger Markdown editor" loading="lazy" sizes="100vw" /></p>

<p>You’ll probably want to keep the Dillinger website open as you read through this guide. That way you can try the syntax as you learn about it. After you’ve become familiar with Markdown, you may want to use a Markdown application that can be installed on your desktop computer or mobile device.</p>

<h2 id="how-does-it-work">How Does it Work?</h2>

<p>Dillinger makes writing in Markdown easy because it hides the stuff happening behind the scenes, but it’s worth exploring how the process works in general.</p>

<p>When you write in Markdown, the text is stored in a plaintext file that has an <code class="language-plaintext highlighter-rouge">.md</code> or <code class="language-plaintext highlighter-rouge">.markdown</code> extension. But then what? How is your Markdown-formatted file converted into HTML or a print-ready document?</p>

<p>The short answer is that you need a <em>Markdown application</em> capable of processing the Markdown file. There are lots of applications available — everything from simple scripts to desktop applications that look like Microsoft Word. Despite their visual differences, all of the applications do the same thing. Like Dillinger, they all convert Markdown-formatted text to HTML so it can be displayed in web browsers.</p>

<p>Markdown applications use something called a <em>Markdown processor</em> (also commonly referred to as a “parser” or an “implementation”) to take the Markdown-formatted text and output it to HTML format. At that point, your document can be viewed in a web browser or combined with a style sheet and printed. You can see a visual representation of this process below.</p>

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Note:</strong> The Markdown application and processor are two separate components. For the sake of brevity, I've combined them into one element ("Markdown app") in the figure below.
</div>

<p><img srcset="https://mdg.imgix.net/assets/images/markdown-flowchart.png?auto=format&amp;fit=clip&amp;w=480 480w,              https://mdg.imgix.net/assets/images/markdown-flowchart.png?auto=format&amp;fit=clip&amp;q=40&amp;w=1080 1080w" src="https://mdg.imgix.net/assets/images/markdown-flowchart.png" class="img-fluid" alt="The Markdown Process" loading="lazy" sizes="100vw" /></p>

<p>To summarize, this is a four-part process:</p>

<ol>
  <li>Create a Markdown file using a text editor or a dedicated Markdown application. The file should have an <code class="language-plaintext highlighter-rouge">.md</code> or <code class="language-plaintext highlighter-rouge">.markdown</code> extension.</li>
  <li>Open the Markdown file in a Markdown application.</li>
  <li>Use the Markdown application to convert the Markdown file to an HTML document.</li>
  <li>View the HTML file in a web browser or use the Markdown application to convert it to another file format, like PDF.</li>
</ol>

<p>From your perspective, the process will vary somewhat depending on the application you use. For example, Dillinger essentially combines steps 1-3 into a single, seamless interface — all you have to do is type in the left pane and the rendered output magically appears in the right pane. But if you use other tools, like a text editor with a static website generator, you’ll find that the process is much more visible.</p>

<h2 id="whats-markdown-good-for">What’s Markdown Good For?</h2>

<p>Markdown is a fast and easy way to take notes, create content for a website, and produce print-ready documents.</p>

<p>It doesn’t take long to learn the Markdown syntax, and once you know how to use it, you can write using Markdown just about everywhere. Most people use Markdown to create content for the web, but Markdown is good for formatting everything from email messages to grocery lists.</p>

<p>Here are some examples of what you can do with Markdown.</p>

<h3 id="websites">Websites</h3>

<p>Markdown was designed for the web, so it should come as no surprise that there are plenty of applications specifically designed for creating website content.</p>

<p>If you’re looking for the simplest possible way to create a website with Markdown files, check out <a href="https://blot.im">blot.im</a>. After you sign up for Blot, it creates a Dropbox folder on your computer. Just drag and drop your Markdown files into the folder and — poof! — they’re on your website. It couldn’t be easier.</p>

<p>If you’re familiar with HTML, CSS, and version control, check out <a href="/tools/jekyll/">Jekyll</a>, a popular static site generator that takes Markdown files and builds an HTML website. One advantage to this approach is that <a href="/tools/github-pages/">GitHub Pages</a> provides free hosting for Jekyll-generated websites. If Jekyll isn’t your cup of tea, just pick one of the <a href="https://jamstack.org/generators/">many other static site generators available</a>.</p>

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Note:</strong> I used Jekyll to create the <i>Markdown Guide</i>. You can view the source code on <a href="https://github.com/mattcone/markdown-guide">GitHub</a>.
</div>

<p>If you’d like to use a content management system (CMS) to power your website, take a look at <a href="/tools/ghost/">Ghost</a>. It’s a free and open-source blogging platform with a nice Markdown editor. If you’re a WordPress user, you’ll be happy to know there’s <a href="https://wordpress.com/support/wordpress-editor/blocks/markdown-block/">Markdown support</a> for websites hosted on WordPress.com. Self-hosted WordPress sites can use the <a href="https://jetpack.com/support/markdown/">Jetpack plugin</a>.</p>

<h3 id="documents">Documents</h3>

<p>Markdown doesn’t have all the bells and whistles of word processors like Microsoft Word, but it’s good enough for creating basic documents like assignments and letters. You can use a Markdown document authoring application to create and export Markdown-formatted documents to PDF or HTML file format. The PDF part is key, because once you have a PDF document, you can do anything with it — print it, email it, or upload it to a website.</p>

<p>Here are some Markdown document authoring applications I recommend:</p>

<ul>
  <li><strong>Mac:</strong> <a href="/tools/macdown/">MacDown</a>, <a href="/tools/ia-writer/">iA Writer</a>, or <a href="/tools/marked-2/">Marked 2</a></li>
  <li><strong>iOS / Android:</strong> <a href="/tools/ia-writer/">iA Writer</a></li>
  <li><strong>Windows:</strong> <a href="https://kde.github.io/ghostwriter/">ghostwriter</a> or <a href="https://markdownmonster.west-wind.com/">Markdown Monster</a></li>
  <li><strong>Linux:</strong> <a href="https://github.com/retext-project/retext">ReText</a> or <a href="https://kde.github.io/ghostwriter/">ghostwriter</a></li>
  <li><strong>Web:</strong> <a href="/tools/dillinger/">Dillinger</a> or <a href="/tools/stackedit/">StackEdit</a></li>
</ul>

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Tip:</strong> <a href="https://ia.net/writer/templates/">iA Writer</a> provides templates for previewing, printing, and exporting Markdown-formatted documents. For example, the "Academic – MLA Style" template indents paragraphs and adds double sentence spacing.
</div>

<h3 id="notes">Notes</h3>

<p>In nearly every way, Markdown is the ideal syntax for taking notes. Sadly, <a href="https://evernote.com/">Evernote</a> and <a href="https://www.onenote.com/">OneNote</a>, two of the most popular note applications, don’t currently support Markdown. The good news is that several other note applications <em>do</em> support Markdown:</p>

<ul>
  <li><a href="/tools/obsidian/">Obsidian</a> is a popular Markdown note-taking application loaded with features.</li>
  <li><a href="/tools/simplenote/">Simplenote</a> is a free, barebones note-taking application available for every platform.</li>
  <li><a href="/tools/notable/">Notable</a> is a note-taking application that runs on a variety of platforms.</li>
  <li><a href="/tools/bear/">Bear</a> is an Evernote-like application available for Mac and iOS devices. It doesn’t exclusively use Markdown by default, but you can enable Markdown compatibility mode.</li>
  <li><a href="/tools/joplin/">Joplin</a> is a note taking application that respects your privacy. It’s available for every platform.</li>
  <li><a href="/tools/boostnote/">Boostnote</a> bills itself as an “open source note-taking app designed for programmers.”</li>
</ul>

<p>If you can’t part with Evernote, check out <a href="https://marxi.co/">Marxico</a>, a subscription-based Markdown editor for Evernote, or use <a href="/tools/markdown-here/">Markdown Here</a> with the Evernote website.</p>

<h3 id="books">Books</h3>

<p>Looking to self-publish a novel? Try <a href="https://leanpub.com/">Leanpub</a>, a service that takes your Markdown-formatted files and turns them into an electronic book. Leanpub outputs your book in PDF, EPUB, and MOBI file format. If you’d like to create paperback copies of your book, you can upload the PDF file to another service such as <a href="https://kdp.amazon.com">Kindle Direct Publishing</a>. To learn more about writing and self-publishing a book using Markdown, read <a href="https://medium.com/techspiration-ideas-making-it-happen/how-i-wrote-and-published-my-novel-using-only-open-source-tools-5cdfbd7c00ca">this blog post</a>.</p>

<h3 id="presentations">Presentations</h3>

<p>Believe it or not, you can generate presentations from Markdown-formatted files. Creating presentations in Markdown takes a little getting used to, but once you get the hang of it, it’s a lot faster and easier than using an application like PowerPoint or Keynote. <a href="https://remarkjs.com">Remark</a> (<a href="https://github.com/gnab/remark">GitHub project</a>) is a popular browser-based Markdown slideshow tool, as are <a href="https://jdan.github.io/cleaver/">Cleaver</a> (<a href="https://github.com/jdan/cleaver">GitHub project</a>) and <a href="https://marp.app/">Marp</a> (<a href="https://github.com/marp-team/marp">GitHub project</a>). If you use a Mac and would prefer to use an application, check out <a href="https://www.decksetapp.com/">Deckset</a> or <a href="https://hyperdeck.io/">Hyperdeck</a>.</p>

<h3 id="email">Email</h3>

<p>If you send a lot of email and you’re tired of the formatting controls available on most email provider websites, you’ll be happy to learn there’s an easy way to write email messages using Markdown. <a href="/tools/markdown-here/">Markdown Here</a> is a free and open-source browser extension that converts Markdown-formatted text into HTML that’s ready to send.</p>

<h3 id="collaboration">Collaboration</h3>

<p>Collaboration and team messaging applications are a popular way of communicating with coworkers and friends at work and home. These applications don’t utilize all of Markdown’s features, but the features they do provide are fairly useful. For example, the ability to bold and italicize text without using the WYSIWYG interface is pretty handy. <a href="/tools/slack/">Slack</a>, <a href="/tools/discord/">Discord</a>, <a href="/tools/wiki-js/">Wiki.js</a>, and <a href="/tools/mattermost/">Mattermost</a> are all good collaboration applications.</p>

<h3 id="documentation">Documentation</h3>

<p>Markdown is a natural fit for technical documentation. Companies like GitHub are increasingly switching to Markdown for their documentation — check out their <a href="https://github.com/blog/1939-how-github-uses-github-to-document-github">blog post</a> about how they migrated their Markdown-formatted documentation to <a href="/tools/jekyll/">Jekyll</a>. If you write documentation for a product or service, take a look at these handy tools:</p>

<ul>
  <li><a href="https://readthedocs.org">Read the Docs</a> can generate a documentation website from your open source Markdown files. Just connect your GitHub repository to their service and push — Read the Docs does the rest. They also have a <a href="https://readthedocs.com/">service for commercial entities</a>.</li>
  <li><a href="/tools/mkdocs/">MkDocs</a> is a fast and simple static site generator that’s geared towards building project documentation. Documentation source files are written in Markdown and configured with a single YAML configuration file. MkDocs has several <a href="https://www.mkdocs.org/user-guide/styling-your-docs/">built in themes</a>, including a port of the <a href="https://readthedocs.org/">Read the Docs</a> documentation theme for use with MkDocs. One of the newest themes is <a href="https://squidfunk.github.io/mkdocs-material/">MkDocs Material</a>.</li>
  <li><a href="/tools/docusaurus/">Docusaurus</a> is a static site generator designed exclusively for creating documentation websites. It supports translations, search, and versioning.</li>
  <li><a href="https://vuepress.vuejs.org/">VuePress</a> is a static site generator powered by <a href="https://vuejs.org/">Vue</a> and optimized for writing technical documentation.</li>
  <li><a href="/tools/jekyll/">Jekyll</a> was mentioned earlier in the section on websites, but it’s also a good option for generating a documentation website from Markdown files. If you go this route, be sure to check out the <a href="https://idratherbewriting.com/documentation-theme-jekyll/">Jekyll documentation theme</a>.</li>
</ul>

<h2 id="flavors-of-markdown">Flavors of Markdown</h2>

<p>One of the most confusing aspects of using Markdown is that practically every Markdown application implements a slightly different version of Markdown. These variants of Markdown are commonly referred to as <em>flavors</em>. It’s your job to master whatever flavor of Markdown your application has implemented.</p>

<p>To wrap your head around the concept of Markdown flavors, it might help to think of them as language dialects. People in New York City speak English just like the people in London, but there are substantial differences between the dialects used in both cities. The same is true for people using different Markdown applications. Using <a href="/tools/dillinger/">Dillinger</a> to write with Markdown is a vastly different experience than using <a href="/tools/ulysses/">Ulysses</a>.</p>

<p>Practically speaking, this means you never know exactly what a company means when they say they support “Markdown.” Are they talking about only the <a href="/basic-syntax/">basic syntax elements</a>, or all of the basic and <a href="/extended-syntax/">extended syntax elements</a> combined, or some arbitrary combination of syntax elements? You won’t know until you read the documentation or start using the application.</p>

<p>If you’re just starting out, the best advice I can give you is to pick a Markdown application with good Markdown support. That’ll go a long way towards maintaining the portability of your Markdown files. You might want to store and use your Markdown files in other applications, and to do that you need to start with an application that provides good support. You can use the <a href="/tools/">tool directory</a> to find an application that fits the bill.</p>

<h2 id="additional-resources">Additional Resources</h2>

<p>There are lots of resources you can use to learn Markdown. Here are some other introductory resources:</p>

<ul>
  <li><a href="https://daringfireball.net/projects/markdown/">John Gruber’s Markdown documentation</a>. The original guide written by the creator of Markdown.</li>
  <li><a href="https://www.markdowntutorial.com/">Markdown Tutorial</a>. An open source website that allows you to try Markdown in your web browser.</li>
  <li><a href="https://github.com/mundimark/awesome-markdown">Awesome Markdown</a>. A list of Markdown tools and learning resources.</li>
  <li><a href="https://dave.autonoma.ca/blog/2019/05/22/typesetting-markdown-part-1">Typesetting Markdown</a>. A multi-part series that describes an ecosystem for typesetting Markdown documents using <a href="https://pandoc.org/">pandoc</a> and <a href="https://www.contextgarden.net/">ConTeXt</a>.</li>
</ul>




  </body>
</html>
