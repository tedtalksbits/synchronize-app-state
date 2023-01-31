# Synchronizing state of Webpage in multiple tabs

This is a simple example of how to synchronize the state of a webpage in multiple tabs.

## Different Approaches

- ✅ **Approach 1: Using LocalStorage**
The approach **I use** is to use the [LocalStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) to use the onstorage event to send messages between tabs.

- ❕ Approach 2: Using Broadcast Channel
Another approach is to use the [Broadcast Channel API](https://developer.mozilla.org/en-US/docs/Web/API/Broadcast_Channel_API) to send messages between tabs.

- ❕ Approach 3: Using Service Worker
Another approach is to use the [Service Worker API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) to send messages between tabs.