+++
# Experience widget.
widget = "experience"  # Do not modify this line!
active = true  # Activate this widget? true/false

title = "Experience"
subtitle = ""

# Order that this section will appear in.
weight = 40

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "January 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "CEO"
  company = "Dgraph Labs, Inc."
  company_url = "https://dgraph.io"
  location = "San Francisco, California"
  date_start = "2016-01-01"
  date_end = ""
  description = """
Dgraph is the world's most advanced graph database. It is horizontally scalable, synchronously replicated, transactional and distributed. It can do arbitrarily deep joins, while minimizing network communication and disk seeks, scaling well as cluster size increases. It is a low-latency, high-throughput database, serving complex queries over multiple independent data sources in real-time.

  """

[[experience]]
  title = "Senior Software Engineer"
  company = "Google"
  company_url = "https://google.com "
  location = "Mountain View, California"
  date_start = "2007-08-01"
  date_end = "2013-05-15"
  description = """
*In reverse chronological order:*

Led a team of engineers for a project to build low latency, high throughput
graph system to consolidate structured data. Replaced various custom backends
with this system, allowing better data sharing and lowering engineering
resources required to launch new knowledge projects. Google's Knowledge Graph
and OneBoxes (weather, movie showtimes, flights etc.) are utilizing this
technology.

Built a knowledge engine which can truly understand user's query using Freebase
Graph, and generate appropriate results. Eventually launched as Knowledge Bar at
google.com for listy queries.

Received OC award for successful launch of *Caffeine*: Google's
incremental indexing system providing 50% fresher results, and the largest
collection of web content ever offered by Google.

Built various solutions tackling size control, index quality and page
freshness issues in a system holding *>100PB* of data.

"""

[[experience]]
  title = "Software Engineering Intern"
  company = "Google"
  company_url = "https://google.com "
  location = "Mountain View, California"
  date_start = "2006-06-06"
  date_end = "2007-01-31"
  description = """
Ported Bigtable's *RowMutation* C++ APIs to Python. Bigtable is a distributed,
scalable, proprietary data storage system owned by Google.

Ported Google Localization Framework from relational DB to Bigtable,
significantly cutting down latency of data retrieval. Implemented search and
logging functionality for various tools in the framework.
"""

+++
