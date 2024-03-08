# Base Structure

<html>
  <head>(Title that is displayed on the web browser tab)</head>
  <Body>(Contains all semantic and non semantic containers)</Body>
</html>

# Semantic

- <header></header>
- <nav></nav> (usually contains hyperlinks)
- <article></article>
- <footer></footer>
- Use to following to format code <strong></strong> and <em></em> to display bold and italic text respectively and can be inside any other semantic or not semantic containers,
- <aside></aside> Usually used as a container of secondary information that complements information or usually used as a sidebar container

# Non-Semantic

- initially the only container there was is <div></div> which can still be use but it is too much work
  to style each of them using CSS depending on the context they are in

- <a></a> Stands for anchor and is used to navigate using hyperlinks using "href" to declare the link and and attributes like "target" to declare if it will be displayed in a new or same tab, use "#" to display same website.

- <p></p> defines a paragraph. The advantage over <div> is that this will have some standard margin/padding values

- <h1></h1> there is headros from 1 to 6

- <ul></ul> unordered list. Each item has to be defined in a <li></li> and items will be listed using a black dot for each

- <ol></ol> ordered list. Each item has to be defined in a <li></li> and items will be listed using a black dot for each

- <img/> it has to be closed in same opening tag, define attributes "src" to define path to image,"alt" to give screen reader a description to be more accesible for special needs users, and "width" and "height"
