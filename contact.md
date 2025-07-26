---
layout: page
title: Contact
---

<div class="container mx-auto px-6 py-16 md:py-24 text-center">
  <h1 class="font-serif-display text-4xl font-bold mb-8">{{ page.title }}</h1>
  <div class="max-w-xl mx-auto">
    <p class="text-lg text-gray-700 mb-8">
      Have a question, a suggestion, or just want to say hello? I'd love to hear from you. Fill out the form below, and I'll get back to you as soon as possible.
    </p>
    <form action="[YOUR_FORM_ACTION_URL]" method="POST" class="text-left">
      <div class="mb-4">
        <label for="name" class="block text-gray-700 font-bold mb-2">Name</label>
        <input type="text" id="name" name="name" class="w-full px-4 py-3 rounded-lg border focus:outline-none focus:ring-2 focus:ring-gray-800" required>
      </div>
      <div class="mb-4">
        <label for="email" class="block text-gray-700 font-bold mb-2">Email</label>
        <input type="email" id="email" name="email" class="w-full px-4 py-3 rounded-lg border focus:outline-none focus:ring-2 focus:ring-gray-800" required>
      </div>
      <div class="mb-6">
        <label for="message" class="block text-gray-700 font-bold mb-2">Message</label>
        <textarea id="message" name="message" rows="5" class="w-full px-4 py-3 rounded-lg border focus:outline-none focus:ring-2 focus:ring-gray-800" required></textarea>
      </div>
      <div class="text-center">
        <button type="submit" class="bg-gray-800 text-white font-bold px-8 py-3 rounded-full hover:bg-gray-900 transition duration-300">Send Message</button>
      </div>
    </form>
  </div>
</div>