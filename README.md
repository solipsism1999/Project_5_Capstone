# Capstone Project: Writer's Block in the Manga Industry

This is a passion project. I am passionate about writing, and have always wanted to try writing manga, but I lack the necessary skills to draw. This was what inspired me to take on this task.

---

## Defining the problem

**What is Writer’s Block?**
- Defined as “the inability to begin or continue writing for reasons other than a lack of basic skill or commitment.”
- Personal Experience: Can be very frustrating, caused me sleepless nights when I was affected by it. Can also happen to artists.
- Put plainly, it is a sudden lack of motivation which results in writers being unable to continue their work.

**Storyboarding, and how writer’s block has a negative effect:**
- Crucial step where creators plan the visual flow of the story, depicting scenes and panel layouts.
- Storyboarding is the bridge between a written script and the final artwork.
- Writer's block can extend to storyboarding, where creators struggle to visualize the scenes and transitions

**Writer’s Block is prevalent in the manga industry:**
- Berserk: Kentaro Miura was known for taking hiatuses due to creative challenges leading to long waits.
- Evangelion: Yoshiyuki Sadamoto took multiple hiatuses which were attributed to creative challenges.
- Hunter X Hunter: Yoshihiro Togashi, experienced writer's block, leading to year-long hiatuses.

**Creators’ relentless workload is worsening the issue:**
- There are many manga creators who end up suffering from their work
- Creators work long hours affecting physical or mental health or suffer direct abuse from the system.
- Leads to a loss of motivation, inability to produce new ideas, and worsens the problem of writer’s block.

**How is AI helping with writer's block?**
- ChatGPT is helping to write next instalment of manga hit One Piece as author runs into writer’s block.
- “Cyberpunk: Peach John” is the world’s first complete AI manga work.

We thus arrive at the following problem statement:

## Problem Statement
“Can we build AI Models that address the problem of writer’s block in the manga industry by helping with ideation and storyboarding?”

---

### Datasets

The 10 genres with the most manga were selected from an anime and manga databse called MyAnimeList (MAL) for this analysis. MyAnimeList provides a wealth of information about anime and manga, including details about the series, such as the plot, characters, and staff involved in their creation. It also offers seasonal anime charts, news, and forums for discussions on various topics related to anime and manga. The site also features aggregated ratings for anime and manga, as well as member counts for each manga and anime.	

---

### Data Dictionary 

|Feature|Type|Dataset|Description|
|----|----|----|----|
|Name                   	        |string  |manga_data.csv |This holds the name of the manga scraped       |
|Description                     	|string  |manga_data.csv |This holds the description of the manga scraped|
|Rating                     	    |float   |manga_data.csv |This holds the user rating of the manga scraped|
|Members			            	|integer |manga_data.csv |Number of members of the scraped manga         |
|Primary Genre 						|string  |manga_data.csv |The primary genre of the scraped manga         |

---

### Action Points to writers

- **Genre Selection:** Aspiring manga writers looking to break into the industry should consider focusing on genres like "Action," "Drama," "Comedy," and "Romance" due to their high popularity and average ratings. These genres have a broader audience base and the potential to attract a dedicated readership.
- **Leverage Emotional Storytelling:** Genres that focus on personal growth, interpersonal relationships, and emotional journeys, such as "Drama" and "Romance," are well-received. Aspiring writers should focus on creating relatable and emotionally resonant characters and stories.
- **Engage in World-Building:** Popular genres like "Action" often incorporate elements of fantasy, magic, and supernatural themes. Writers should invest in world-building and creative storytelling to transport readers to captivating and imaginative worlds.
- **Exploring Multiple Genres:** Don't be afraid to experiment with multiple genres or hybrid genres. Some of the most innovative and exciting manga emerge from creative genre combinations.

By following these conclusions and recommendations, manga writers can increase their chances of creating compelling and popular manga series that resonate with readers and stand out in the competitive world of manga. 

---

### Conclusions

We have created a way to automated ideation and storyboarding using generative AI and modelling tools. These tools can provide several benefits to manga writers and help them overcome writer's block:
- **Inspiration and Creativity Boost:** The tool can provide fresh and creative ideas, helping manga writers overcome creative blocks. It can offer novel scenarios, character interactions, and plot twists, sparking new inspiration.
- **Overcoming Writer's Block:** Our tool can break the writer's block by providing a starting point. Writers can modify, expand upon, or adapt these prompts to fit their narrative vision.
- **Reducing Writer's Stress:** By taking on some of the ideation workload, the tool can reduce the stress and pressure associated with coming up with new story ideas and storyboards on a consistent basis.
- **Collaboration:** The generated panels produced by our tool can serve as a starting point for collaboration between writers and artists. Writers can present the generated concepts to artists, who can then refine and visualize them. This is especially a boon to people who like to write, but cannot draw.

### Future Work

- Improve the text generation model, train it to generate multiple scenarios.
- Work on training an image generator on a custom dataset, and not rely on a pre-trained model.

**Note**

Please download the below link to the saved model. The code uses this model to generate text.
Link: https://drive.google.com/drive/folders/1YdKtxkVgQEsPaDiGsIwVIO9aXIna-pDY?usp=sharing