# API
A Web API (Web Application Programming Interface) is a set of rules and protocols that allows different software systems—especially web-based applications—to communicate with each other over the internet using HTTP.

In simple terms:

It lets different applications send and receive data between each other—kind of like ordering food from a restaurant via a waiter. The API is the waiter between your app and the server.

Key Characteristics:
	•	HTTP-based: Works over the web using standard HTTP methods like GET, POST, PUT, and DELETE.
	•	RESTful (usually): Most modern Web APIs follow REST principles (Representational State Transfer), which make them simple and scalable.
	•	Data Format: Usually uses JSON or XML to send/receive data.
	•	Stateless: Each request is independent; the server doesn’t remember previous requests (unless session/state is explicitly handled).

 Research 3 apps you use and find out what APIs they might be using
 Operamini
 GitHub
 Safari

 OPERAMINI
 Opera Mini, as a lightweight web browser, does not expose a public “API” in the traditional sense for developers to integrate with directly. However, Opera Mini uses a variety of internal APIs and third-party services to enhance its functionality, particularly for data compression, browsing, and other features.

When you refer to “Keys API” in the context of Opera Mini, I assume you’re asking about some key features or key APIs Opera Mini might use internally to provide its services. Below are a few possible API integrations and technologies that Opera Mini utilizes:
Keys API use BY Operamini



1. Compression Proxy (Internal API)

Opera Mini is well-known for its data-saving feature, which compresses webpages via Opera’s own servers before they are sent to the device.
	•	How it works: When a user requests a page, the request is sent to Opera’s proxy servers. These servers retrieve the full page, compress it (removing unnecessary content), and then send a lightweight version to the user’s device.
	•	No public API for this process, but the compression proxy can be seen as a critical part of how Opera Mini delivers its speed and data-saving functionality.
2. Geolocation API

Opera Mini can access location-based services (like showing local news or weather). It uses the HTML5 Geolocation API, a standard browser API to access a device’s geographical position.

3. Push Notification APIs (Mobile)

On mobile platforms (Android and iOS), Opera Mini might use push notification services for alerts and updates.
	•	Google Firebase Cloud Messaging (FCM) for Android devices.
	•	Apple Push Notification Service (APNs) for iOS devices.

These APIs enable the Opera Mini app to receive notifications even when it’s not actively in use.

4. Search and Content APIs

Opera Mini integrates search engines (e.g., Google, Bing, or Yahoo) to perform web searches directly from the browser.
	•	Opera might use Google Custom Search API or other third-party search APIs to retrieve search results for users.
 5. Web and Media APIs

Opera Mini might also integrate with HTML5 Web APIs like:
	•	Canvas API for rendering graphics.
	•	Video/Audio APIs for handling media content on web pages.
 6. Ad APIs

Opera Mini uses ads for its revenue model. They might use Google AdMob or other third-party ad services to show banner ads or interstitial ads.

GitHub
GitHub offers a robust set of APIs, and the term “Keys API” typically refers to endpoints related to SSH keys, GPG keys, or API authentication keys (tokens) that help manage access to GitHub accounts or repositories.
Keys API use by github
1. SSH Keys API

Used to list, add, or remove SSH public keys associated with a GitHub user account. These keys are used to authenticate Git operations via SSH.
2. GPG Keys API

GPG keys are used to verify the integrity and authorship of commits and tags.
3. Personal Access Tokens (API Keys)

These are not managed via an API for security reasons, but they act like API keys and are required to authenticate API calls.
	•	When calling the API, you typically include your token in the header:
 4. OAuth Apps & GitHub Apps APIs

GitHub provides API endpoints to manage:
	•	OAuth access tokens
	•	GitHub App installations
	•	App permissions

These are essential when integrating GitHub with external tools or services securely.

SAFARI 
Safari is a web browser developed by Apple Inc. It is the default browser on macOS, iOS, and iPadOS devices.
1. WebKit-Specific and Standard Web APIs

Safari is built on the WebKit engine, and it supports a wide range of HTML5 and JavaScript APIs. Some important ones include:
2. iCloud Keychain Integration (Safari Feature)

Safari also integrates with iCloud Keychain, which securely stores:
	•	Passwords
	•	Credit card info
	•	Wi-Fi logins

While there’s no public API to directly access iCloud Keychain from a website, Safari can automatically suggest and fill in passwords and autofill data when users visit login forms.
3. Limitations in Safari Compared to Other Browsers

Safari is more privacy-focused and sometimes restricts or delays implementation of APIs such as:
	•	Push notifications (supported only on macOS)
	•	Web Bluetooth API (not supported)
	•	File System Access API (limited support)


 
