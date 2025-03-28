# MyKB

MyKB is an app for tagging, storing, and retrieving document-based knowledge.

For those who desire to store and organize significant amounts of knowledge, filesystem-based organization schemes do not scale. Hierarchical folder/file structures force us to choose between:

- Fast ingestion (create a new file as we read/watch and take notes), but with slow retrieval (info is spread across multiple files and often in different folder directories)
  - 
- or slow ingestion (choosing a predefined folder layout and then parsing each valuable piece of knowledge that we read/watch into all of its relevant places) in order to speed up retrieval
  - Even retrieval is only moderately fast, as large folder hierarchies take a fair amount of mental energy to navigate, as each folder drilldown requires us to remember whether what we seek is in one subtree or the other.
  - And in practice, valuable pieces of knowledge can often be used in various ways, making it ultimately impossible to find just one perfect location for that piece of knowledge

The fastest way to manage larger knowledge bases, in the experience of the author, is to read/watch (and structure notes as necessary), and then to create an entry with potentially many tags. Tagging knowledge is obviously not new, as evidenced by the widespread use of blog "tag clouds". However, this approach only scales to a small number of tags, and is very constrained by the visual layout of the typical web site.

MyKB is written for a knowledge learner who is processing information (reading, watching, listening, etc) and is able to create potentially many meaningful tags for that knowledge item (blog post, YouTube video, etc). *Meaningful* tagging typically means one (or both) of two things:

- the learner already has a good understanding of how they might use the knowledge in the future, and can create (or reuse) a set of tags that captures those possible uses
- the learner creates MANY tags (often a dozen or more) for a knowledge item based on the content actually in the
