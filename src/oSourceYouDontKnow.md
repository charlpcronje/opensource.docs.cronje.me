# Open Source Libraries you don't know about

## The Fuck

[View on GitHub](https://github.com/nvbn/thefuck)

The Fuck is a magnificent app, inspired by a [@liamosaur](https://twitter.com/liamosaur/) [tweet](https://twitter.com/liamosaur/status/506975850596536320) tweet, that corrects errors in previous console commands.

### Eamples for `The Fuck`

```sh
➜ apt-get install vim
E: Could not open lock file /var/lib/dpkg/lock - open (13: Permission denied)
E: Unable to lock the administration directory (/var/lib/dpkg/), are you root?

➜ fuck
sudo apt-get install vim [enter/↑/↓/ctrl+c]
[sudo] password for nvbn:
Reading package lists... Done
...
```

```sh
➜ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master


➜ fuck
git push --set-upstream origin master [enter/↑/↓/ctrl+c]
Counting objects: 9, done.
...
```

```
➜ puthon
No command 'puthon' found, did you mean:
 Command 'python' from package 'python-minimal' (main)
 Command 'python' from package 'python3' (main)
zsh: command not found: puthon

➜ fuck
python [enter/↑/↓/ctrl+c]
Python 3.4.2 (default, Oct  8 2014, 13:08:17)
...
```

```sh
➜ git brnch
git: 'brnch' is not a git command. See 'git --help'.

Did you mean this?
    branch

➜ fuck
git branch [enter/↑/↓/ctrl+c]
* master
```

```
➜ lein rpl
'rpl' is not a task. See 'lein help'.

Did you mean this?
         repl

➜ fuck
lein repl [enter/↑/↓/ctrl+c]
nREPL server started on port 54848 on host 127.0.0.1 - nrepl://127.0.0.1:54848
REPL-y 0.3.1
...
```

If you're not afraid of blindly running corrected commands, the `require_confirmation` [settings](https://github.com/nvbn/thefuck#settings) option can be disabled:

```sh
➜ apt-get install vim
E: Could not open lock file /var/lib/dpkg/lock - open (13: Permission denied)
E: Unable to lock the administration directory (/var/lib/dpkg/), are you root?

➜ fuck
sudo apt-get install vim
[sudo] password for nvbn:
Reading package lists... Done
...
```

## Partytown

[Visit Website](https://partytown.builder.io/)

### Run Third-Party Scripts From A Web Worker
Partytown is a lazy-loaded library to help relocate resource intensive scripts into a [web worker](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API), and off of the main thread. Its goal is to help speed up sites by dedicating the main thread to your code, and offloading third-party scripts to a web worker.

Even with a fast and highly tuned website following all of today’s best practices, it’s all too common for your performance wins to be erased the moment third-party scripts are added. By third-party scripts we mean code that is embedded within your site, but not directly under your control. A few examples include: analytics, metrics, ads, A/B testing, trackers, etc.

## SuperTokens

[Visit Website](https://supertokens.com/)

Configuring basic auth features like email verification, session management, refresh tokens, expiration, forgot password feature etc. takes a lot of time and SuperTokes in giving it out of the box. That is what I was looking for :) The simplicity is the key here. I saw plenty of other “safe” solutions, but none of them was simple like yours. I heard great opinions about SuperTokens, that’s why I chose it.

- Pre built UI
Sign up / sign in forms (via our frontend SDK) that can be embedded on your website natively

- 45 minutes
9/10 developers do the quick setup in under 45 minutes

- Feature segmentation
Pick only the features you need and see docs relevant to your use case (we call it ‘recipes’)

- Simple data model
Fewer database tables and simpler configuration due to our modular structure

- Support
Quickest response times (<1hour) for support - available on Discord, email and calls for 18 hours / day

- Priced for startups
Generous limits and pricing for our managed service and free forever for self hosted!

## Meilisearch

[Visit Website](https://www.meilisearch.com/)

- Shape a delightful search experience in a snap
An open-source, lightning-fast, and hyper-relevant search engine that fits effortlessly into your apps, websites, and workflow.

- The next generation of search
Meilisearch is a flexible and powerful user-focused search engine that can be added to any website or application.

- Lightning fast
Search-as-you-type returns answers in less than 50 milliseconds. That's faster than the blink of an eye!

- Plug ‘n play
Deploy in a matter of minutes. Smart presets let you start searching through your data with zero configuration.

- Flexible
Send data to Meilisearch however you want—no need to match a schema or convert your dataset to a compatible format.

- Typo tolerant
Everyone makes mistakes! If typos break your search experience, many users will leave thinking what they were looking for just wasn't there.

## Zinc Search Engine

[Visit Website](https://zincsearch.com/)

- Feature 1
Full Text Search
You can index large amounts of text Zinc and search instantly

- Feature 2
Embedded Web UI
Zinc is a batteries-included setup. Embedded UI provides an easy way to get started and interact with your data. No need to set up a separate GUI like kibana.

- Feature 3
Compatibility with Elasticsearch API
Ingestion and Search APIs are elasticsearch compatible so you could easily migrate applications. Docs coming soon.

- Feature 4
Schemaless Indexes
No need to work hard to define schema ahead of time. ZincSearch automatically discovers schema so you can focus on search and analysis.

- Feature 5
S3 and MinIO for index storage (experimental)
Store data in S3 and MinIO for low cost, virtually infinite durable storage without the hassle of managing storage.

- Feature 6
Aggregations
Do faceted search and analyze your data.

## tRPC

[Visit Website](https://trpc.io/)

End-to-end typesafe APIs made easy

The client doesn't import any code from the server, only a single TypeScript type. The import type declaration is fully erased at runtime. tRPC transforms this type into a fully typesafe client.

![gif](https://storage.googleapis.com/trpc/trpcgif.gif)


## NocoDB

[Visit Website](https://nocodb.com/)

### Open Source Airtable Alternative

NocoDB is an open source #NoCode platform that turns any database into a smart spreadsheet.

`NocoDB will be the single most important tool in the #nocode industry.` Despite being a non developer, I was able to build a business workflow within an hour by connecting to an existing MySQL database (AWS RDS). NocoDB is so flexible that it can be integrated with many business verticals."
Vasyl Rakivnenko

Founder/CEO Servired

### Create Endless Solutions
It is free & self-hostable. Let your imagination be thy limit
Create unlimited grid view, gallery view, form view from your own data
Search, sort, filter columns and rows with ultra ease

## Danfo JS

[Visit Website](https://danfo.jsdata.org/)

Danfo.js is heavily inspired by the [Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) library and provides a similar interface and API. This means users familiar with the Pandas API can easily use Danfo.js.

### Main Features

- Danfo.js is fast and supports `Tensorflow.js's` tensors out of the box. This means you can convert `Danfo.js` DataFrames to Tensors, and vice versa.
- Easy handling of missing data (represented as NaN, undefined, or null) in data
- Size mutability: columns can be inserted/deleted from DataFrames
- Automatic and explicit alignment: objects can be explicitly aligned to a set of labels, or the user can simply ignore the labels and let `Series`, `DataFrame`, etc. automatically align the data for you in computations
- Powerful, flexible, `groupby` functionality to perform split-apply-combine operations on data sets, for both aggregating and transforming data
- Make it easy to convert Arrays, JSONs, List or Objects, Tensors, and differently-indexed data structures into DataFrame objects
- Intelligent label-based slicing, fancy indexing, and querying of large data sets
- Intuitive `merging` and `joining` data sets
- Robust IO tools for loading data from `flat-files` (CSV and delimited), Excel, and JSON data format.
- Powerful, flexible, and intiutive API for plott`ing DataFrames and Series interactively.
- Timeseries-specific functionality: date range generation and date and time properties.
- Robust data preprocessing functions like `OneHotEncoders`, `LabelEncoders`, and scalers like `StandardScaler` and `MinMaxScaler` are `supported` on `DataFrame` and Series

## Mantine.dev

[Visit Website](https://mantine.dev/)

Build fully functional accessible web applications faster than ever – Mantine includes more than 120 customizable components and hooks to cover you in any situation

- Free and open source
All packages have MIT license, you can use Mantine in any project

- TypeScript based
Build type safe applications, all components and hooks export types

- No annoying focus ring
Focus ring will appear only when user navigates with keyboard

- Core components library
Mantine core library includes all essential components: inputs, buttons, modals, popovers, typography elements, layout management, etc.

- Theming
Extend default theme with any amount of additional colors, replace shadows, radius, spacing, fonts and many other properties to match your design requirements.
Mantine theme is just an object, you can subscribe to it in any part of application via context and use it to build your own components.

- Hooks library
Mantine comes with more than 30 hooks to manage state and UI to help you build custom components.
All hooks that are used to build Mantine components are exported from @mantine/hooks package, hooks do not depend on components packages, you can use them independently in any react application.

- Transitions API
Animate presence with premade transition or build your own animation with simple API, all Mantine components support custom transitions

- Notifications system
A fully featured notifications system integrates seamlessly with your Mantine theme.

- Rich text editor
A Quill.js based rich text editor: handles images uploads, supports embedded video, integrates seamlessly with your Mantine theme

- Explore Mantine UI
Mantine UI is a set of more than 120 responsive components built with Mantine. All components support dark/light color scheme and Mantine theme customizations. Mantine UI is free for everyone.

[View Components](https://ui.mantine.dev/)

## Amplication

[Visit Website](https://amplication.com/)

Instantly generate `Authorization`, `Admin UI`, `GraphQL`, `Logging`, `RestAPI`

- Just code what matters.
Amplication is an open-source development tool. It helps you develop quality Node.js applications without spending time on repetitive coding tasks.

### Front-end developer

- Use Amplication UI or CLI to create your app
- Design data models and create REST & GraphQL APIs without coding.
- No need for server-side development skills since Amplication auto-generates back-end code.
- You can focus entirely on developing your next great app

[Get Started with Front-end](https://app.amplication.com/)

### Full-stack developer

- Amplication auto-generates an app based on TypeScript and Node.js.
- Generated apps include NestJS, Prisma, REST & GraphQL API, a React admin UI, logging, authentication and authorization.
- Safely customize your generated app Node.js code using your favorite IDE.
- Decide whether to download the app within a Docker container that’s ready for deployment or to deploy to the Amplication cloud.
- At any point you’re free to download the source code and continue development elsewhere.

[Get Started with back-end](https://app.amplication.com/)