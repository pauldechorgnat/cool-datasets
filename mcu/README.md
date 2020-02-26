<h1>mcu</h1>

<p>These datasets contain data from IMDB website on Marvel Cinematic Universe as of July 2019. It is made to illustrate relationships between (some of) the actors, realisators, producers, characters and movies in a Graph Oriented DataBase Management System (such as Neo4J).</p>
<h2>Description of the files</h2>
<table>
<tr><th>Name</th>
<th>Description</th>
</tr>
<tr><td><code>characters.csv</code></td><td>List of characters in the MCU .</td></tr>
<tr><td><code>person.csv</code></td><td>List of persons that play a role in the MCU (actors, realisators, producers). </td></tr>
<tr><td><code>movies.csv</code></td><td>List of movies in the MCU.</td></tr>
<tr><td><code>characters_appears_in_movie.csv</code></td><td>List of appearances of characters in the MCU movies.</td></tr>
<tr><td><code>person_plays_characters.csv</code></td><td>List of actors for each character in the MCU..</td></tr>
<tr><td><code>person_produces_movie.csv</code></td><td>List of producers for each movie in the MCU.</td></tr>
<tr><td><code>person_realises_movie.csv</code></td><td>List of realisators for each movie in the MCU.</td></tr>
</table>

<h2>Description of the attribute</h2>
<p>The features are described for all the files.</p>

<table>
<tr>
<th>Name</th>
<th>Description</th>
</tr>
<tr>
<td>character</td>
<td>name of the character (serves as id for the character)</td>
</tr>
<tr>
<td>nconst</td>
<td>id of the peson</td>
</tr>
<tr>
<td>primaryName</td>
<td>name of the person</td>
</tr>
<tr>
<td>birthYear</td>
<td>year of birth of the person</td>
</tr>
<tr>
<td>deathYear</td>
<td>year of death of the person</td>
</tr>
<tr>
<td>primaryProfession</td>
<td>list of professions of the person</td>
</tr>
<tr>
<td>tconst</td>
<td>id of the movie</td>
</tr>
<tr>
<td>primaryTitle</td>
<td>title of the movie</td>
</tr>
<tr>
<td>startYear</td>
<td>year of release of the movie</td>
</tr>
<tr>
<td>runtimeMinutes</td>
<td>duration of the movie (in minutes)</td>
</tr>
<tr>
<td>genres</td>
<td>list of genres of the movie</td>
</tr>
</table>

<div class="alert-warning">
The dataset is not actually very accurate because IMDB provides only some of the actors per movie. I might change it in the future.</div>