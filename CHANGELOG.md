# Changelog

## 0.4.1

- Faster, quieter start: the app opens on the home screen and loads no web page; your browsers wait on the home screen and open when you click them (or when the AI agent needs one)
- Closed browsers show their last preview and site on the home screen

## 0.4.0

- Copy anything from a chat: select any text, or use the copy buttons on answers, code blocks, tables (they paste straight into Excel) and tool results
- Right-click menu in the app: copy, paste, select all, open or copy links, copy images, spelling suggestions
- Windows notifications when the AI agent needs your approval or finishes while you are in a browser or another app; click the notification to open the chat. The taskbar button shows when the agent is working or waiting, and the top bar counts waiting approvals
- Chats: search titles and messages, rename, grouped by Today / Yesterday / Previous 7 days; Ctrl+N starts a new chat
- Edit and resend a message, retry the last answer, scroll-to-bottom button, drafts kept for every chat, the Up arrow recalls your last message and Esc stops the agent
- Drop or paste files and screenshots into the message box; they are added to the workspace for the agent
- Errors are shown instead of failing silently
- Signing out, clearing history and deleting passwords, extensions, chats or Chrome connections ask for a second click
- Light, dark or system theme; the window remembers its size and position
- A model is selected automatically on first start

## 0.3.0

- Use your own Chrome: the new **api14 AI Browser for Chrome** extension (`api14-ai-browser-chrome`, included with the installer) connects any Chrome profile to the app
- New **Chrome** screen: step-by-step install guide that opens the extension folder and `chrome://extensions` for you, one-time approval for every Chrome, a name for each one and a switch for agent access
- See the windows and tabs of every connected Chrome live; switch to, open and close tabs from the app
- See and manage the extensions installed in that Chrome: turn them on or off, open their options, remove them
- The AI agent works in your Chrome tabs just like in the app's browsers: read pages, click, type, extract tables, screenshots, save as PDF, history and downloads; it asks before turning a Chrome extension on or off
- Local and private: the app listens only on this computer and accepts only Chrome extensions you approved

## 0.2.2

- Browsers work like Chrome profiles: close a browser and its sign-ins, cookies and tabs are kept; click it to continue where you left off. Closing the last tab closes the browser.
- "All browsers" menu to reopen closed browsers, close button and middle-click on the browser strip, right-click to edit
- Pick a color for each browser
- The AI agent plans first and keeps its plan updated; when a task runs long it finishes with a summary of what was done and what is left
- The AI agent detects loops (the same action repeated) and changes strategy
- Downloads: when a click saves a file, the AI agent sees where it was saved and reads it
- The AI agent can read PDF, Word (docx), PowerPoint (pptx), Excel, CSV, JSON, zip listings and images

## 0.2.1

- Incognito browser: cookies only in memory, no history
- Per-browser language, SOCKS5 / HTTP proxy with connection test, user agent and new-tab page
- Page translation, Chrome extensions from an unpacked folder
- Password manager with Windows encryption; the agent fills saved logins without seeing them
- Files: drag into web pages, copy images to the clipboard, add to chat, import your own files, previews
- New settings screen with sections and paginated history
- Agent: works inside iframes, more reliable clicks in background tabs, new tools (translate, configure browser, fill saved login, print, developer tools, full screen)
- AI media: cheapest model by default with automatic fallback; speech saved as WAV when a model only returns PCM
- Customizable Quick open links; menus follow the system language

## 0.2.0

First public release of api14 AI Browser Agent for Windows.

- Chrome-like browser with separate browser profiles, tabs, bookmarks, downloads, history, find in page, zoom and Chrome shortcuts
- AI agent with visible plan, reasoning, tool calls, parallel subagents and approvals
- 400+ AI models through api14.com with Connect with api14 sign-in
- Browser automation: read, click, type, extract tables, upload files, vision questions
- Google Ads and Meta Ads workflows
- Excel, PDF and PowerPoint reports; AI image, video and speech generation
- Customizable Quick open links
- Automatic updates from GitHub releases
