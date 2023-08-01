# llm-utils

The following contains the code for the application from this [Medium blog post](https://medium.com/@rafalotufo/unlocking-ai-potential-with-openai-function-calls-a-deep-dive-into-simplifying-data-retrieval-945be3647c09). The blog post
explains how function calls work and is helpful to understand this code.

## How to

To run the application, first you need an OPENAPI_API_KEY environment variable with
your OPENAI key. You will have access to a key if you sign up for API use.

Then, you should follow these instructions to install dependencies, export the API key,
and run the application:

```
> pip install -r requirements.txt
> export OPENAI_API_KEY=<YOUR-API-KEY>
> python wikipedia-ai.py "What was the cause of the Silicon Valley Bank crash in 2023?"

In March 2023, Silicon Valley Bank experienced a collapse and seizure by the California
Department of Financial Protection and Innovation (DFPI). The collapse was triggered by
a bank run on its deposits, which was caused by central bank-endorsed interest rate hikes
and concerns about the bank's liquidity. The DFPI appointed the Federal Deposit
Insurance Corporation (FDIC) as the receiver of the bank. The FDIC established a
bridge bank successor called Silicon Valley Bridge Bank, which assumed ongoing
business operations. First Citizens Bank & Trust Company later acquired the commercial
banking business of Silicon Valley Bridge Bank from the FDIC.
```

Another example:

```
> python wikipedia-ai.py "What is the Apple glasses that was announced in 2023 and what does it do?"

Apple Vision Pro, also known as Apple glasses, is an upcoming mixed reality headset
developed by Apple Inc. It was announced in June 2023 and is set to be available for
purchase in 2024. The Vision Pro is a standalone device that integrates digital media
with the real world and allows users to interact with the system through motion gestures,
eye tracking, and voice input. The headset runs on visionOS, a derivative of iOS
designed for extended reality apps. It can also be tethered to a Macintosh. The
development of the Vision Pro has been influenced by the acquisition of augmented
reality companies Metaio and Vrvana, as well as collaborations with brands like
Nike. The device features a laminated glass display, an adjustable headband, and
various sensors, cameras, and microphones. It uses the Apple M2 system on a chip
and supports custom optical inserts for users with prescription glasses. The software,
visionOS, offers a 3D user interface and compatibility with a wide range of apps,
including familiar iPhone and iPad apps, games, and virtual meeting platforms like
Microsoft Teams and Zoom.
```
