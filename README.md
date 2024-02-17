**ChatGPT Story Generator**

This is a story generation code using ChatGPT, a language model developed by OpenAI. The code allows you to generate various types of stories based on different prompts. Below is a guide on how to use the code effectively.

**Options for Message Sections**

There are three options for the message_sections_role parameter:

User: Represents the end user interacting with the assistant. This option is used to mimic user inputs.
Assistant: Allows you to control what the assistant says to the user.
System: Used for injecting information or processing data in the middle without displaying it to the user.
For this code, the user role has been utilized to mimic user interactions.

**Available Options for Story Generation**


You can generate stories based on different prompts by customizing the following lists:

python
Copy code
mylist = ["a story on", "An essay on", "a terrifying story on", "a romantic story on", "a comedy story on"]
location = ["india", "USA", "UK", "France", "Building", "Park", "Cinema"]
person = ["long person", "Short person", "Black person", "White person", "Brown person", "person with glasses", "person with umbrella"]
types = ["action", "Romantic", "sensational", "adventure"]
mylist: Contains various prompts or themes for the story.
location: Provides options for different settings or locations where the story can take place.
person: Specifies different types of characters that can be included in the story.
types: Represents different genres or types of stories that can be generated.
Feel free to customize these lists to generate stories according to your preferences or specific requirements.

**Usage**
Clone the repository.
Install the necessary dependencies. such as Anaconda to run run the code in Jupyter notebook in local machine or you can use the Google Colab to run online.
Run the code and follow the prompts to generate stories.
Example
python
Copy code
# Generate a romantic story set in the UK featuring characters "long person" and "person with glasses"
prompt = "a romantic story on"
location = "UK"
characters = ["long person", "person with glasses"]
story_type = "Romantic"

generated_story = generate_story(prompt, location, characters, story_type)
print(generated_story)
Note
Ensure that you have the required permissions and adhere to OpenAI's usage policies when using the ChatGPT model.

Feel free to explore and experiment with different prompts and options to create diverse and engaging stories!

**the key.txt file contains the key of the ChatGPT 3.5 you can get this from the ChatGPT website**
https://platform.openai.com/api-keys




