# Exno.9-To explore and understand the various prompting techniques used for generating videos through AI models. 

# Date: 17/11/2025

# Register no.: 212223040122


## Aim:
To explore and understand the various prompting techniques used for generating videos through AI models. The objective is to identify how different types of prompts (simple, detailed, motion-based, stylistic) impact the coherence, style, and quality of the generated videos across different classes of AI tools.

# Algorithm: 
Explore how various prompting techniques can be used to generate and manipulate video content (e.g., animations, visual effects, video summaries) using AI models.

## Procedure:
1. Familiarization with AI Tools for Video Generation:The procedure began by differentiating the capabilities of various AI video tools.
   
   Runway (Gen-2): A creative generative model. Converts text prompts into novel video clips (text-to-video). Suitable for artistic shots, animations, and visual effects.
   
   Synthesia / DeepBrain AI: AI avatar models. Generate video of a photorealistic avatar speaking a text script. They do not create descriptive scenes.
   
   Pictory: A content repurposing model. Assembles video by finding relevant stock video clips that match a text script and adding an AI voice-over.
   
2. Create a Simple Prompt:A short and direct description to establish a baseline for generation.
   
   Prompt 1 (Simple): "A person walking in a park."
   
   This prompt was used to observe the most basic interpretation of a scene by a creative generator (Runway) versus a content repurposer (Pictory).
   
3. Create a Detailed Prompt:A descriptive prompt adding context, subject details, and secondary actions.
   
   Prompt 2 (Detailed): "A person in a red jacket walking along a sunny park path, with birds flying in the sky, and a dog running beside them."
   
   This prompt was used to assess how well a model (like Runway) handles multiple, specific instructions (color, lighting, multiple actors) and to observe the failure point of a tool like Pictory, which would be unable to find a single stock clip matching all details.
   
4. Observation and Comparison:

     The simple prompt on Runway Gen-2 resulted in a generic 3-5 second clip of a person in a vague green space. The same prompt in Pictory successfully found a stock clip of a person walking in a park.
   
     The detailed prompt on Runway Gen-2 produced a more visually specific scene: the model rendered the red jacket and used the "sunny" keyword to create bright, high-contrast lighting. The model attempted to add the dog and birds, showing an ability to handle multiple elements, though motion consistency can vary.
   
   The detailed prompt would fail in Pictory, as its stock library is unlikely to contain a clip matching all elements (red jacket, sunny, and a dog). This highlights the fundamental difference between generating content and assembling content. Avatar tools (Synthesia) could not process either prompt as intended.
   
5. Prompting Techniques Overview:

| **Prompt Type**      | **Description**                                                              | **Tool Effectiveness**                                                                                    |
| -------------------- | ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| **Simple Prompt**    | Short, direct description (e.g., "A car driving.")                           | **Runway:** Generates a basic, often generic video. <br> **Pictory:** Finds a relevant stock clip.        |
| **Detailed Prompt**  | Richly descriptive (e.g., "A red car driving on a wet street at night.")     | **Runway:** Adds specific details (color, reflections). <br> **Pictory:** Fails or finds a partial match. |
| **Motion Prompt**    | Includes camera/subject motion (e.g., "A time-lapse... camera zooming out.") | **Runway:** Interprets motion keywords as camera commands. <br> **Other tools:** Not applicable.          |
| **Stylistic Prompt** | Defines the aesthetic (e.g., "An animated scene of a cat...")                | **Runway:** Changes entire visual style. <br> **Other tools:** Not applicable.                            |


  
6. Optimization Strategies:
   
     Use vivid adjectives (e.g., "glowing," "ancient") and adverbs (e.g., "slowly," "rapidly") to guide the model.
   
     Choose the AI tool based on the desired output: Runway for creative scenes, Pictory for turning articles into videos, and Synthesia for presentations.
   
     For generative models (Runway), use keywords as commands for camera ("low-angle," "tracking shot") and style ("cinematic," "3D render").
   
     Iterate based on model output; refine the prompt to correct or enhance the generated video.
   
## Output:
Prompt 1 (Simple): "A person walking in a park."

  Output: 

  

https://github.com/user-attachments/assets/19d45617-5a94-4ea3-8a0e-8895d5529d4d



    
  Drive link:
    
Prompt 2 (Detailed): "A person in a red jacket walking along a sunny park path, with birds flying in the sky, and a dog running beside them."
  
  Output:


    
  Drive link:
  
## Conclusion:

The experiment successfully demonstrated that prompting techniques are highly dependent on the type of AI video tool being used. The most critical step is tool selection. A simple prompt that works for a content repurposer (Pictory) will produce generic results in a creative generator (Runway) and fail in an avatar tool (Synthesia).

