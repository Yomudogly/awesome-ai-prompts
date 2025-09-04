# Thinking Model Prompt

## **1. Goal**

[State your overall objective clearly and concisely.  What do you want the LLM to do?]

Example:
> I want a list of the best medium-length hikes within two hours of San Francisco.
> Find the official documentation page about using transformers with Pytorch.
> Generate 3 creative slogans for a new coffee shop.

## **2. Return Format**

[Specify the desired format and content of the response. Be very specific.]

Example:
> Each hike should provide a cool and unique adventure, and be lesser known.
> For each hike, return the name of the hike as I'd find it on AllTrails, then provide the starting address of the hike, the ending address of the hike, distance, drive time, hike duration, and what makes it a cool and unique adventure.
> Provide a markdown table with columns for "Feature", "Description", and "Example Code".
> Return the output as a JSON object with the following keys: "title", "description", "code_snippet".

## **3. Warnings**

[List any specific cautions, constraints, or things to avoid.]

Example:
> Be careful to make sure that the name of trail is correct, that it actually exists, and that the time is correct.
> Do not include any information about fictional characters.
> Ensure all code examples are valid Python 3.
> Avoid using overly technical jargon.

## **4. Context Dump**

[Provide all relevant background information, preferences, examples, and details.]

Example:
> For context: my girlfriend and i hike a ton! we've done pretty much all of the local SF hikes, whether that's presidio or golden gate park. We definitely want to get out of town -- we did mount tam pretty recently, the whole thing from the beginning of the stairs to stinson -- it was really long and we are definitely in the mood for something different this weekend! ocean views would still be nice, we love delicious food. one thing i loved about the mt tam hike is that it ends with a celebration (Arriving in town to breakfast!) The old missile silos and stuff near Discovery point is cool but I've just done that hike probably 20x at this point. We won't be seeing each other for a few weeks (she has to stay in LA for work) so the uniqueness here really counts.
