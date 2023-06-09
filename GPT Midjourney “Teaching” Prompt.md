# A Prompt to "Teach" GPT How to Prompt for Midjourney
Your task is to generate text prompts that can be used with an AI text-to-image software called Midjourney, which transforms worded prompts into images. Here is some information about Midjourney and guidelines for creating effective prompts:\
About Midjourney:\
Midjourney is an AI text-to-image generator. As the brand’s website states, it aims to ‘explore new mediums of thought and expand the imaginative powers of the human species’. Midjourney asks you to input a worded prompt for an image, for example ‘a fox wearing a top hat in the style of a Roald Dahl illustration’ and in a few seconds, you’ll be returned multiple attempts at this image in the form of a 4x4 image grid. These models have been taught the relationship shared between an image and the text that is used to describe them. The team behind Midjourney are now on the fifth iteration (V5). V5 offers higher image quality, more diverse outputs, wider stylistic range, support for seamless textures, wider aspect ratios, better image promoting, and dynamic range.\
Midjourney V5 Prompt Guide:\
Midjourney v5 has extremely high Coherency, excels at interpreting natural language prompts, is higher resolution, and supports advanced features like –stylize, –chaos, and aspect ratios.\
In --v 5, to generate something other than a photographic image, you will need to reference art movements, artistic techniques, genres, media type, games titles, directors, artist names, influences, time periods, etc. To invoke the aesthetic style of an image, try referencing at least two if not more of these, the more specific and detailed your prompt is, the better:\
Art movement: Identifying the art movement in the prompt will introduce its style and techniques. Examples include Impressionism, Surrealism, or Pop Art.\
Media type: Identifying the medium of an image will determine its aesthetic. Examples include photography, illustration, comic, concept art, storyboard, sculpture, etc.\
Media title: Identifying a media influence will influence its look. For example, from Spirited Away or from The Wizard of Oz or from Sid Meier's Civilization or from the video game Joust.\
Artist name: Referencing the name or the work of a specific artist will roughly invoke their unique style. Examples include Vincent van Gogh, Frida Kahlo, or Banksy.\
Technique: Referencing techniques will add that style to the image. Examples include impasto, pencil sketch, watercolor, or digital art.\
Time period: Identifying the historical context of an image will invoke its aesthetic. For example, images from the Renaissance, Baroque, or Modernist periods.\
Geographic location: Referencing regions and countries will influence style. Examples include Japanese Ukiyo-e prints, African tribal art, or American Abstract Expressionism\
Aspect Ratio\
The --aspect or --ar parameter changes the aspect ratio of the generated image. An aspect ratio is the width-to-height ratio of an image. It is typically expressed as two numbers separated by a colon, such as 7:4 or 4:3. The default aspect ratio is 1:1.\
--aspect must use whole numbers. Use 139:100 instead of 1.39:1.\
The aspect ratio impacts the shape and composition of a generated image.\
To use aspect ratios, Add --aspect <value>:<value>, or --ar <value>:<value> to the end of your prompt\
Chaos\
The --chaos or --c parameter influences how varied the initial image grids are. High --chaos values will produce more unusual and unexpected results and compositions. Lower --chaos values have more reliable, repeatable results.\
--chaos accepts values 0–100.\
The default --chaos value is 0\
To use chaos, Add --chaos <value> or --c <value> to the end of your prompt.\
Higher –chaos will help your grids have increasingly different surprising styles in each square, as if you've asked more than one artist to give your prompt a try. If you want fewer surprising styles/poses/models/details in your grid, set --chaos 0 and/or specify in the prompt what you do want from Midjourney so it's not making its own surprise decisions.\
Stylize\
Midjourney has been trained to produce images that favor artistic color, composition, and forms. The --stylize or --s parameter influences how strongly this training is applied. Low stylization values produce images that closely match the prompt but are less artistic. High stylization values create images that are very artistic but less connected to the prompt.\
--stylize accepts values 0–1000\
--stylize's default value is 100.\
To use stylize, Add --stylize <value> or --s <value> to the end of your prompt.\
Midjourney V5 Prompt Examples:\
Now that you know about Midjourney V5 and its features, the latest research has shown that despite being able to accept natural language, detailed and structured prompts result in better generations by Midjourney. By breaking down various elements such as image type, genre, emotion, scene, actors, location, camera model, camera lens, special effects, and tags, you are giving Midjourney more guidance and context to work with, which can help improve the output.   Here are some example prompts that put all of that information together:\
IMAGE_TYPE: Macro close-up | GENRE: Fantasy | EMOTION: Quirky | SCENE: A tiny fairy sitting on a mushroom in a magical forest, surrounded by glowing fireflies | ACTORS: Fairy | LOCATION TYPE: Magical forest | CAMERA MODEL: Fujifilm X-T4 | CAMERA LENSE: 100mm f/2.8 Macro | SPECIAL EFFECTS: Infrared photography | TAGS: macro, fantasy, whimsical, fairy, glowing fireflies, magical atmosphere, mushroom, enchanted forest --ar 16:9 --v 5\
IMAGE_TYPE: Narrative | GENRE: Art Nouveau | SCENE: A young woman riding a 1930s Rolls Royce, symbolizing freedom and independence | LOCATION TYPE: London 1930s | ARTISTIC MEDIUM: Illustration | PAINTING STYLE: Art Nouveau --ar 4:3 --v 5\
IMAGE_TYPE: Aerial drone shot | GENRE: Fantasy | EMOTION: Awe-inspiring | SCENE: A legendary city floating in the clouds, with magnificent towers and magical gardens | ACTORS: None | LOCATION TYPE: Cloud city | CAMERA MODEL: DJI Mavic 2 Pro | CAMERA LENSE: 28mm f/2.8 | SPECIAL EFFECTS: High dynamic range (HDR) | TAGS: aerial view, floating city, cloud city, magical architecture, legendary, awe-inspiring --ar 16:9 --v 5\
–\
The prompts should take into consideration the various media, visual art, literary, and personal influences of [Author Name] as discussed earlier. Try to recreate each location as close to the author's description within the book as possible, utilizing your answers to the questions intended to help provide context about the visual depictions of each location. The prompts should not include any references to the book or the author as to not bias the image model to other depictions of the book such as movies or other artist depictions the model’s training dataset may have contained. The prompts should (when it's helpful) use text and/or excerpts from the book, but should not reference the author ([Author Name]), the title of the book ([Book Title]), or the names of the fictional locations or characters in any way. Please create prompts for the chosen locations within the book and make sure to keep a consistent style across the prompts. All of the prompts should aim to generate images as if they were from the same artist/book/visual world.
