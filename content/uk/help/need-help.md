---
author: 'Hugo Authors'
title: 'I need help'
---

<br>
<div class="form-help container mx-auto py-10">
  <form id='needForm' class='w-10/12 md:3w-3/4 lg:w-1/2 m-auto'>
  <label class="block text-m font-medium text-white-700" for="fname">First name:</label>
  <input class="inp block w-full rounded-md border py-2 dark:border-transparent pl-7 pr-12 mt-4 focus:border-indigo-500 focus:ring-indigo-500 sm:text-m" type="name" id="fname" name="fname" placeholder="Name"><br>
  <label for="email">Email address:</label><br>
  <input class="inp block w-full rounded-md border py-2 dark:border-transparent pl-7 pr-12 mt-4 focus:border-indigo-500 focus:ring-indigo-500 sm:text-m" type="email" id="email" name="email" placeholder="example@email.com"><br>
  <label for="text">What help do you need?</label><br>
  <textarea type="text" id="text" name="text" placeholder="I need ..." rows="5" cols="28" class="inp textarea__help block mt-4 pt-4 w-full rounded-md border dark:border-transparent pl-7 pr-12 focus:border-indigo-500 focus:ring-indigo-500 sm:text-m""></textarea><br><br>
  <div class='hidden border p-2 mb-3' id='sending-mess'></div>
  <input class='px-10 py-2 bg-red-600 text-white hover:bg-purple-500' style= 'cursor: pointer;' type="submit" value="Submit">
</form>
</div>

<!--more-->


{{< css.inline >}}

<style>
.emojify {
	font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}


@media screen and (max-width:650px) {
  .nowrap {
    display: block;
    margin: 25px 0;
  }
}
</style>

{{< /css.inline >}}
