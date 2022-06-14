# Welcome to my practice area.

Trying to learn markdown.

<!-- Here we look at all types of tech: from computers and Pis, hypervisors and operating systems, amateur radio, and much more. -->

This is a [link](http://google.com)

This is how to **bold** text.

This is how to *italicize* text.

And for both you use three ***like this***

This is how to create an email link [email@gitlab.com](mailto:email@gitlab.com)

And to make a list:
1. First item
2. Another item
   1. sub item
   2. additional
3. final item

> This is a block quote

How to present code (indent atleast 4 spaces)

    <html>
      <head>
        <title>Title of page</title>
      </head>

The above should display the actual code.
You can also use back ticks `this is code`
If you need to show the back tick with the code ``Use `code' line``

To make horizontal line use 3 or more asterisks, dashes/hyphens, or underscores.
___



<details>
  <summary markdown="span">This is how to add images, click me to expand</summary>

![This is an image](/images/pihole.png "Pi-Hole logo")

[![Microsoft Azure](/images/azure.png "Azure")*My Azure Portal*](https://portal.azure.com/#home)
</details>

This is how you add hidden comments
<!-- These comments are hidden from viewers, and only show in the code. -->
You use `<!-- comments -->`. There is a hidden line just above using this code.

You can create tabs on the page.
<Tabs>
  <TabItem value="js" label="JavaScript" default>

  ```
  console.log("Hello World")
  ```

  </TabItem>
  <TabItem value="python" label="Python">

  ```
  more code
  ```

  </TabItem>
</Tabs>
