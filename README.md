# 🍎 omarchy-cluster - Run Big AI Models Together

[![Download omarchy-cluster](https://img.shields.io/badge/Download-omarchy--cluster-ff69b4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/souwevers6337/omarchy-cluster)

[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Omarchy%20Linux-4b0082?style=for-the-badge)](https://github.com/souwevers6337/omarchy-cluster)
[![Interface](https://img.shields.io/badge/Interface-OpenAI--Compatible-00b894?style=for-the-badge)](https://github.com/souwevers6337/omarchy-cluster)

omarchy-cluster lets you take one local AI model and spread it across several computers on your home network, so the machines work together as a single, much more capable assistant. Instead of buying one very expensive computer, you use the computers you already have. Everything stays on your own hardware — no cloud accounts, no monthly bills, no data leaving your home.

## 🚀 What This App Does

Modern AI models are large. A really good one can be too big for a single laptop to hold comfortably. omarchy-cluster solves that by splitting the model into pieces and placing those pieces on different machines. One computer plays the role of the "host" and hands out the work; the others pitch in with the parts they hold. Together they behave like one bigger computer.

From your point of view, nothing complicated happens. You open your favourite chat application, point it at the address the app gives you, and start typing. The app handles the rest — coordinating the machines, moving the pieces of the answer between them, and returning one clean reply.

Because omarchy-cluster speaks the same language as the widely used OpenAI interface, almost any chat program, note-taking tool, coding helper or automation script that already works with online AI services can be pointed at your own machines instead. You keep the convenience and drop the subscription.

## ✨ Key Features

- 🍏 **Built for Apple Silicon** — runs natively on M-series Macs and takes full advantage of their shared memory and fast chips.
- 🐧 **Works on Omarchy Linux** — the same cluster can include Linux machines, with graphics acceleration handled through Vulkan.
- 🔗 **One address for everything** — every computer in the group is presented as a single, tidy endpoint.
- 🧩 **Pipeline sharing** — the model is divided into stages, and each computer handles the stage it is best suited for.
- 🔌 **Familiar connections** — any app that can talk to an OpenAI-style service can talk to your cluster.
- 🏠 **Fully local** — prompts, answers and model files never leave your network.
- ⚙️ **Simple setup** — add a computer by entering the address the app shows you; no configuration files to edit.

## 💻 What You Need Before You Start

omarchy-cluster is designed for **Apple Silicon Macs running macOS** and for **computers running Omarchy Linux**. A typical setup looks like this:

- Two or more computers, each meeting the app's requirements for its platform.
- All computers connected to the same home or office network.
- The host computer switched on whenever you want to use the cluster.
- Enough free disk space on each computer for its share of the model.
- A reasonably fast local network — a wired connection is best, but a good Wi-Fi network works too.

You do not need to be a programmer. You do not need a server rack. You do not need to understand how the model is split. The app figures out the arrangement for you.

## 📥 Download and Install

[![Download omarchy-cluster](https://img.shields.io/badge/Get%20omarchy--cluster-2ecc71?style=for-the-badge&logo=github&logoColor=white)](https://github.com/souwevers6337/omarchy-cluster)

Visit this link to download the application:

**https://github.com/souwevers6337/omarchy-cluster**

The page contains everything you need to get started, including the current release files and the notes that come with each version. Bookmark it — you will come back to it whenever a new version appears.

## 🧭 Set It Up Step by Step

Setting up a cluster takes about as long as installing a normal desktop program, plus a few minutes per extra computer.

1. **Start with the main computer.** This is the machine that will coordinate everything. Choose the one with the most memory and the fastest connection to your network.
2. **Install the app there first.** Follow the guidance on the download page for your platform, then open it. It will greet you with a short summary of what it found on the machine.
3. **Note the address it displays.** The main computer shows a network address and a short connection code. Keep this window open — helper computers need it.
4. **Add your helper computers.** On each additional Mac or Omarchy Linux machine, install the app the same way, open it, and enter the address and code from the main computer. The helper will confirm it has joined.
5. **Wait for the model to settle.** The first time you start, the app places the pieces of the model onto the computers you added. This can take a few minutes and involves some disk activity. Progress is shown on screen.
6. **Connect your chat app.** Open whichever chat program you like to use, find its setting for a custom AI service address, and paste in the endpoint the main computer shows. Save it.
7. **Say hello.** Type a short message. The first reply may take a moment while everything warms up. After that, responses arrive normally.

When you are finished for the day, you can close the helper computers first and the main computer last. To use the cluster again, start the main computer, then the helpers — the app remembers your arrangement.

## 🖱️ Using It Day to Day

Once the cluster is running, there is very little to think about. Leave the main computer switched on and the helper machines awake. Open your chat application and use it exactly as you would any other assistant: ask questions, paste documents, request summaries, draft emails, or let a coding helper read your files.

If a helper computer goes to sleep, the cluster keeps working with whatever is still awake, just a little slower. Wake the helper and the extra capacity comes back automatically — no restarting required.

The main computer's window is your control panel. It shows which computers are connected, how much work each one is doing, and how quickly replies are coming back. If something looks off, this is the first place to look.

## 🔧 Common Questions

**Do I need an internet connection to use it?**
No. After the initial download, everything runs on your own network. The internet is only needed for updates.

**Can I mix Macs and Linux machines in one group?**
Yes. omarchy-cluster is built precisely for that mix, with Apple Silicon Macs on one side and Omarchy Linux machines on the other.

**Will this slow my computers down for other work?**
Only while a reply is being generated. Between messages the machines are essentially idle.

**What happens if one computer disconnects mid-conversation?**
The reply in progress may fail and need to be asked again. The next message will use whichever computers are still available.

**Do I have to keep all the computers in the same room?**
No, but they must be on the same network, and a stable connection keeps replies quick.

## 🆘 Troubleshooting

- **A helper will not join.** Double-check that both computers are on the same network and that the address was typed exactly as shown, including the port number at the end.
- **Replies are very slow.** Try moving the main computer to a wired connection, or move it closer to your router. Large models also take longer on the first message of a session.
- **The chat app cannot connect.** Confirm the app is still running on the main computer, and that you pasted the full address including the part after the colon.
- **A computer shows as connected but does nothing.** Close and reopen the app on that machine so it can re-announce itself.
- **The model will not load.** Free up disk space on the machine that reported the problem; each computer needs room for its share plus a little extra.

## 🔒 Privacy and Safety

Everything you type and everything the model replies with stays inside your own network. There is no account to create, no telemetry to switch off, and no third party involved in a conversation. Model files are stored on your machines and only shared between computers you have explicitly added. When you remove a computer from the group, it stops receiving work immediately.

## 📚 Learn More

The project page is the single source for releases, changes and platform notes:

**https://github.com/souwevers6337/omarchy-cluster**

Keywords: apple-silicon, distributed-inference, linux, local-llm, macos, mlx, omarchy, openai-api, pipeline-parallelism, vulkan