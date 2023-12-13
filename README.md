## **Pull Request Message Assistant**

### **The Demand 🤔**

The **Pull Request Message Assistant** was born out of a simple demand: What if a tool could effortlessly consolidate all the carefully crafted commit messages, making it a breeze to write pull request messages at work?

### **The Problematic 😓**

In my daily coding grind, I diligently craft beautiful commit messages. However, when the time comes for my shiny new integration to shine in a pull request, I find myself spending more time than necessary on the message. It's a bit counterproductive, considering the effort already invested in creating aesthetically pleasing commits. Over time, this leads to a dilemma: Do I compromise on the commit messages to save time on pull requests? Not the ideal approach to maintaining code, in my opinion.

Commits should be good enough for a potential rollback due to a rare workflow error. That's where the value of version control systems (VCS) truly shines.

In an ideal world, pull requests serve as documentation. However, relevance is key. And that's where this tool steps in.

### **The Goal 🎯**

The tool aims to seamlessly integrate with my workflow, which I'll outline below.

# **Workflow Magic ✨**

### **1. Code 👨‍💻**

Code with the mindset of short integrations—small packs of code that serve a single purpose.

### **2. Commits ✍️**

When a short integration concludes or when you want to swiftly address a different aspect of a larger integration, it's commit time.

*Remember, commit either as you go or at the end of your big integration. However, doing it at the end might be more tedious and requires recalling every detail.*

Keep commits concise with one or two simple phrases. Bullet points work too, but avoid the brevity trap. Write more if your bullet points are only one or two words.

### **3. TOOL TIME 🛠️**

Simply use the tool, whether inline (CLI) or via the web interface by providing the path to your codebase. The self-hosted web client automatically detects your branch and author details in local GIT. It then generates a Markdown text containing your PR message.

### **4. The Pull Request 🚀**

Copy the result from the tool and paste it into your PR message. Done!

# Development, where to start?

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
