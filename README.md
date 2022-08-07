# Spark Sessions

Educational content for the Spark Sessions

## Philosophy
When students enter 42's core curriculum they might only have ever programmed 4 or 5 C Piscine modules. So when these students start their core curriculum they might get overwhelmed by a project like `ft_printf`.
To help students tackle such a relatively complex project, Spark Sessions were created. By exploring a couple relevant concepts in a structured way, we hope to jumpstart the designer mindset that is needed for building larger projects.

Instead of following essentially a glorified tutorial, students are grouped together and asked a few questions on the pdf. The point of this should be to encourage peer-to-peer learning as well as learning how to learn by
looking up the answers together. In the end they are given a simplified task regarding what the spark session is about to solidify their understanding.

Each session is hosted by 1 or more moderators, they are students that are very comfortable with the project. They help the attendees solve any misunderstood points but their task is not to give the answer straight away.
They should act much like C.A.T's, asking the questions in order to guide them to the answer.

See `./philosophy/` for more information.

## Development
Install `NodeJS >= 16.x`

Run:
```
git clone --recursive git@github.com:codam-coding-college/spark-sessions.git
cd spark-sessions
chmod -R 777 hooks/
cp hooks/* .git/hooks/
```
