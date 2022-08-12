---
layout: home
title: Tailwind CSS Lists - Flowbite
description: Use the typography plugin from Flowbite to apply styles to all inline elements like headings, paragraphs, lists, and images using a single format class
group: components
toc: true

previous: List group
previousLink: components/list-group/
next: Modals
nextLink: components/modal/
---

## Unordored list

Use this default example of a checbkox element in a checked and unchecked state.

{{< example id="default-checkbox-example" github="forms/checkbox.md" show_dark=true >}}
<h2 class="mb-2 text-lg font-semibold text-gray-900 dark:text-white">Password requirements:</h2>
<ul role="list" class="max-w-md space-y-1 text-gray-500 list-disc list-inside dark:text-gray-400">
    <li>
        At least 10 characters (and up to 100 characters)
    </li>
    <li>
        At least one lowercase character
    </li>
    <li>
        nclusion of at least one special character, e.g., ! @ # ?
    </li>
</ul>
{{< /example >}}

### Icon

{{< example id="default-checkbox-example" github="forms/checkbox.md" show_dark=true >}}
<h2 class="mb-2 text-lg font-semibold text-gray-900 dark:text-white">Password requirements:</h2>
<ul role="list" class="max-w-md space-y-1 text-gray-500 list-inside dark:text-gray-400">
    <li class="flex items-center">
        <svg class="w-4 h-4 mr-1.5 text-green-500 dark:text-green-400 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
        At least 10 characters
    </li>
    <li class="flex items-center">
        <svg class="w-4 h-4 mr-1.5 text-green-500 dark:text-green-400 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
        At least one lowercase character
    </li>
    <li class="flex items-center">
        <svg class="w-4 h-4 mr-1.5 text-gray-400 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM8.707 7.293a1 1 0 00-1.414 1.414L8.586 10l-1.293 1.293a1 1 0 101.414 1.414L10 11.414l1.293 1.293a1 1 0 001.414-1.414L11.414 10l1.293-1.293a1 1 0 00-1.414-1.414L10 8.586 8.707 7.293z" clip-rule="evenodd"></path></svg>
        At least one special character, e.g., ! @ # ?
    </li>
</ul>
{{< /example >}}

### Nested
{{< example id="default-checkbox-example" github="forms/checkbox.md" show_dark=true >}}
<ul class="space-y-4 text-gray-500 list-disc list-inside dark:text-gray-400">
    <li>
        List item one
        <ol class="pl-5 mt-2 space-y-1 list-decimal list-inside">
            <li>You might feel like you are being really "organized" o</li>
            <li>Nested navigation in UIs is a bad idea too, keep things as flat as possible.</li>
            <li>Nesting tons of folders in your source code is also not helpful.</li>
        </ol>
    </li>
    <li>
        List item two
        <ul class="pl-5 mt-2 space-y-1 list-decimal list-inside">
            <li>I'm not sure if we'll bother styling more than two levels deep.</li>
            <li>Two is already too much, three is guaranteed to be a bad idea.</li>
            <li>If you nest four levels deep you belong in prison.</li>
        </ul>
    </li>
    <li>
        List item three
        <ul class="pl-5 mt-2 space-y-1 list-decimal list-inside">
            <li>Again please don't nest lists if you want</li>
            <li>Nobody wants to look at this.</li>
            <li>I'm upset that we even have to bother styling this.</li>
        </ul>
    </li>
</ul>
{{< /example >}}

## Ordered list

Use this default example of a checbkox element in a checked and unchecked state.

{{< example id="default-checkbox-example" github="forms/checkbox.md" show_dark=true >}}
<h2 class="mb-2 text-lg font-semibold text-gray-900 dark:text-white">Top students:</h2>
<ol role="list" class="max-w-md space-y-1 text-gray-500 list-decimal list-inside dark:text-gray-400">
    <li>
        <span class="font-semibold text-gray-900 dark:text-white">Bonnie Green</span> with <span class="font-semibold text-gray-900 dark:text-white">70</span> points
    </li>
    <li>
        <span class="font-semibold text-gray-900 dark:text-white">Jese Leos</span> with <span class="font-semibold text-gray-900 dark:text-white">63</span> points
    </li>
    <li>
        <span class="font-semibold text-gray-900 dark:text-white">Leslie Livingston</span> with <span class="font-semibold text-gray-900 dark:text-white">57</span> points
    </li>
</ol>
{{< /example >}}

### Nested

Use this default example of a checbkox element in a checked and unchecked state.

{{< example id="default-checkbox-example" github="forms/checkbox.md" show_dark=true >}}
<ol class="space-y-4 text-gray-500 list-decimal list-inside dark:text-gray-400">
   <li>
      List item one
      <ul class="pl-5 mt-2 space-y-1 list-disc list-inside">
         <li>You might feel like you are being really "organized" o</li>
         <li>Nested navigation in UIs is a bad idea too, keep things as flat as possible.</li>
         <li>Nesting tons of folders in your source code is also not helpful.</li>
      </ul>
   </li>
   <li>
      List item two
      <ul class="pl-5 mt-2 space-y-1 list-disc list-inside">
         <li>I'm not sure if we'll bother styling more than two levels deep.</li>
         <li>Two is already too much, three is guaranteed to be a bad idea.</li>
         <li>If you nest four levels deep you belong in prison.</li>
      </ul>
   </li>
   <li>
      List item three
      <ul class="pl-5 mt-2 space-y-1 list-disc list-inside">
         <li>Again please don't nest lists if you want</li>
         <li>Nobody wants to look at this.</li>
         <li>I'm upset that we even have to bother styling this.</li>
      </ul>
   </li>
</ol>
{{< /example >}}

## Default

Use this default example of a checbkox element in a checked and unchecked state.

{{< example id="default-checkbox-example" github="forms/checkbox.md" show_dark=true >}}
<ul role="list" class="max-w-md divide-y divide-gray-200 dark:divide-gray-700">
   <li class="pb-3 sm:pb-4">
      <div class="flex items-center space-x-4">
         <div class="flex-shrink-0">
            <img class="w-8 h-8 rounded-full" src="/docs/images/people/profile-picture-1.jpg" alt="Neil image">
         </div>
         <div class="flex-1 min-w-0">
            <p class="text-sm font-medium text-gray-900 truncate dark:text-white">
               Neil Sims
            </p>
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
               email@flowbite.com
            </p>
         </div>
         <div class="inline-flex items-center text-base font-semibold text-gray-900 dark:text-white">
            $320
         </div>
      </div>
   </li>
   <li class="py-3 sm:py-4">
      <div class="flex items-center space-x-4">
         <div class="flex-shrink-0">
            <img class="w-8 h-8 rounded-full" src="/docs/images/people/profile-picture-3.jpg" alt="Neil image">
         </div>
         <div class="flex-1 min-w-0">
            <p class="text-sm font-medium text-gray-900 truncate dark:text-white">
               Bonnie Green
            </p>
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
               email@flowbite.com
            </p>
         </div>
         <div class="inline-flex items-center text-base font-semibold text-gray-900 dark:text-white">
            $3467
         </div>
      </div>
   </li>
   <li class="py-3 sm:py-4">
      <div class="flex items-center space-x-4">
         <div class="flex-shrink-0">
            <img class="w-8 h-8 rounded-full" src="/docs/images/people/profile-picture-2.jpg" alt="Neil image">
         </div>
         <div class="flex-1 min-w-0">
            <p class="text-sm font-medium text-gray-900 truncate dark:text-white">
               Michael Gough
            </p>
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
               email@flowbite.com
            </p>
         </div>
         <div class="inline-flex items-center text-base font-semibold text-gray-900 dark:text-white">
            $67
         </div>
      </div>
   </li>
   <li class="py-3 sm:py-4">
      <div class="flex items-center space-x-4">
         <div class="flex-shrink-0">
            <img class="w-8 h-8 rounded-full" src="/docs/images/people/profile-picture-5.jpg" alt="Neil image">
         </div>
         <div class="flex-1 min-w-0">
            <p class="text-sm font-medium text-gray-900 truncate dark:text-white">
               Thomas Lean
            </p>
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
               email@flowbite.com
            </p>
         </div>
         <div class="inline-flex items-center text-base font-semibold text-gray-900 dark:text-white">
            $2367
         </div>
      </div>
   </li>
   <li class="pt-3 pb-0 sm:pt-4">
      <div class="flex items-center space-x-4">
         <div class="flex-shrink-0">
            <img class="w-8 h-8 rounded-full" src="/docs/images/people/profile-picture-4.jpg" alt="Neil image">
         </div>
         <div class="flex-1 min-w-0">
            <p class="text-sm font-medium text-gray-900 truncate dark:text-white">
               Lana Byrd
            </p>
            <p class="text-sm text-gray-500 truncate dark:text-gray-400">
               email@flowbite.com
            </p>
         </div>
         <div class="inline-flex items-center text-base font-semibold text-gray-900 dark:text-white">
            $367
         </div>
      </div>
   </li>
</ul>
{{< /example >}}

## Description list

Use this default example of a checbkox element in a checked and unchecked state.

{{< example id="default-checkbox-example" github="forms/checkbox.md" show_dark=true >}}
<dl class="max-w-md text-gray-900 divide-y divide-gray-200 dark:text-white dark:divide-gray-700">
    <div class="flex flex-col pb-3">
        <dt class="mb-1 text-gray-500 md:text-lg dark:text-gray-400">Email address</dt>
        <dd class="text-lg font-semibold">yourname@flowbite.com</dd>
    </div>
    <div class="flex flex-col py-3">
        <dt class="mb-1 text-gray-500 md:text-lg dark:text-gray-400">Home address</dt>
        <dd class="text-lg font-semibold">92 Miles Drive, Newark, NJ 07103, California, USA</dd>
    </div>
    <div class="flex flex-col pt-3">
        <dt class="mb-1 text-gray-500 md:text-lg dark:text-gray-400">Phone number</dt>
        <dd class="text-lg font-semibold">+00 123 456 789 / +12 345 678</dd>
    </div>
</dl>
{{< /example >}}

## With icons

Use this default example of a checbkox element in a checked and unchecked state.

{{< example id="default-checkbox-example" github="forms/checkbox.md" show_dark=true >}}
<ul role="list" class="mb-8 space-y-4 text-left text-gray-500 dark:text-gray-400">
    <li class="flex items-center space-x-3">
        <!-- Icon -->
        <svg class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
        <span>Individual configuration</span>
    </li>
    <li class="flex items-center space-x-3">
        <!-- Icon -->
        <svg class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
        <span>No setup, or hidden fees</span>
    </li>
    <li class="flex items-center space-x-3">
        <!-- Icon -->
        <svg class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
        <span>Team size: <span class="font-semibold text-gray-900 dark:text-white">1 developer</span></span>
    </li>
    <li class="flex items-center space-x-3">
        <!-- Icon -->
        <svg class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
        <span>Premium support: <span class="font-semibold text-gray-900 dark:text-white">6 months</span></span>
    </li>
    <li class="flex items-center space-x-3">
        <!-- Icon -->
        <svg class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
        <span>Free updates: <span class="font-semibold text-gray-900 dark:text-white">6 months</span></span>
    </li>
</ul>
{{< /example >}}

## Horizontal

Use this default example of a checbkox element in a checked and unchecked state.

{{< example id="default-checkbox-example" github="forms/checkbox.md" show_dark=true >}}
<ul class="flex flex-wrap items-center justify-center mb-6 text-gray-900 dark:text-white">
    <li>
        <a href="#" class="mr-4 hover:underline md:mr-6 ">About</a>
    </li>
    <li>
        <a href="#" class="mr-4 hover:underline md:mr-6">Premium</a>
    </li>
    <li>
        <a href="#" class="mr-4 hover:underline md:mr-6 ">Campaigns</a>
    </li>
    <li>
        <a href="#" class="mr-4 hover:underline md:mr-6">Blog</a>
    </li>
    <li>
        <a href="#" class="mr-4 hover:underline md:mr-6">Affiliate Program</a>
    </li>
    <li>
        <a href="#" class="mr-4 hover:underline md:mr-6">FAQs</a>
    </li>
    <li>
        <a href="#" class="mr-4 hover:underline md:mr-6">Contact</a>
    </li>
</ul>
{{< /example >}}

