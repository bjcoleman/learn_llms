# Setup LM Studio

We will use **LM Studio** to download and run language models locally on your Mac. It is not installed by default, so you will get it from the official site.

> **LM Studio vs Bionic:** The homepage at [lmstudio.ai](https://lmstudio.ai/) currently promotes **Bionic**, a newer, separate app for agent-style work (projects, coding/research, optional cloud models). Its interface is different from what this guide shows.
>
> For this course, use **LM Studio** (the 0.4.x app), not Bionic. Download it from [lmstudio.ai/download](https://lmstudio.ai/download). LM Studio is the right tool for browsing, downloading, loading, and chatting with local models.

## Download and Install

1. Open [lmstudio.ai/download](https://lmstudio.ai/download) in your browser.
2. Click **Download** for your operating system (for example, **Download for Mac**).
3. Open the downloaded installer / app and launch **LM Studio**.

## First Launch Setup

The first time you open LM Studio, you will see a short set of setup screens.

### Your first model

One screen offers a default model to download. Recently this has been **`gemma-4-e4b`** (about **6.86 GB**).

![Your first model](firstmodel.png)

You do **not** need this model for the course. Choose one of the following:

- Click **Skip for now** (or **Skip →** in the top right) to continue without downloading it.
- Click **Download gemma-4-e4b** if you want an extra model available later. It will appear under **My Models** along with anything else you install.

If you start the download, you can continue setup while it finishes in the background:

![Downloading first model](downloadingmodel.png)

Either choice is fine. Later we will download the course model, **Qwen3.5 9B**.

### Advanced settings

You may also see an **Advanced settings** screen:

![Advanced settings](advancedsettings.png)

Recommended defaults for this course:

- Leave **Developer Mode** **off** (keeps the UI simpler).
- **Start local LLM service on login** can stay **on** (convenient) or be turned **off** (uses fewer background resources when you are not using LM Studio).

Then click **Continue to LM Studio →**.

### Promo screens

After setup, LM Studio may show feature announcements (for example, **LM Link**). These are optional. Check **Do not show this again**, click **Next**, or close the dialog with **X**.

![Promo screen](promoscreen.png)

## Download a Model

1. Open **Discover → Model Search** from the left sidebar, or press `⌘⇧M`.

![Model Search](modelsearch.png)

2. In the search bar, type `Qwen3.5 9B`.
3. Select the official **Qwen3.5 9B** result.
4. Click **Download** (about **5.98 GB**). This usually takes about **5 minutes**, depending on your network — wait until it finishes.

![Model Download](modeldownload.png)

If the model is already on your machine, you may see **Use in New Chat** instead of **Download**.

## Load the Model and Chat

After the download is complete:

1. Click the **Chat** icon on the left sidebar, or press `⌘1`.

![Chat](chat.png)

2. At the top center of the screen, open the menu that says **Select a model to load**, or press `⌘L`.
3. Choose **`Qwen3.5 9B`**. Wait a moment for it to load into memory.
4. Type a prompt in the chat box at the bottom and press **Enter** to generate text locally.
