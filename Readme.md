###Project Idea and Initial Planning

SpriteSheet manipulation and organization application designed spceifically for Scalable Vector Graphics. Allow users to better catalogue the multitude of elements that make up an SVG sprite sheet and allow users to apply styling to multiple paths simultaneously. 

Will be build on Ruby and implemnented using the Ruby on Rails Framework

###Models

I will need to familiar myself with Ruby on Rails prior to the development of my app as I am not familiar with Ruby as of yet, and I am unfamiar with their Models/Schema format as well as the Ruby language. For now I will build my documentation using a more SQL/Mongo vernacular.

####Sheet

This model will hold the data for the entire sheet, including the name of teh sheet as well as the various 'frames' and 'sets' that make up that sheet. This model will also contain the size of the sheet and will change as more rows and columns are added to the sheet.

####Columns and Rows

My App will allow users to set their number of frames for each animation by setting their column/rows to be equal to the number of frames for their animations. Additional columns and rows can be added to increade the number of frames in an animation as well as add more unique animation sets.

I will implement a model for both Column as well as Row.
(at first columns will represent frames and rows will be used to add additional addinamtion sets, however I will want make these two models interchangable in their function and allow the user to set them according to how they arrange their spritesheets.)

####Sprite

This model will hold all the data for individual frames of an animation. Some properties of this model will be sprite size, perhaps a frame number, the column or 'set' it belongs to as well any styling or notes used by the user.

####Paths

This model is used for the paths that make up the SVG sprite itself. Properties of this model may include the class and id of the paths as well relevant styling or other elements linked to the paths.

###Styling and other Elements

This model will contain a list of important elements that need to be referenced in the manipulation of the SVG, however emplementation of this element may not be attainable by the time version one is deployed and will likely be a feature in version two.

###Wire Frames and Architecture



###Technologies Used

####Ruby on Rails

the use of Ruby is not vital to this project however I will be using Ruby on Rails as the work I want to do proferssionally will require me to understand this language and framework.

####React.js

I will be using to develop my front end application, Unless after learning Ruby I find some better alternative that I currently am unaware of.


###Addition Resources

As stated earlier, Ruby and Rails is not a language I ahve used before, however I will be taking my understanding the principles of CRUD and applying them to a "new" language/framework. Below is a link to course material I used to get familiar with Ruby.

https://www.youtube.com/watch?v=fmyvWz5TUWg