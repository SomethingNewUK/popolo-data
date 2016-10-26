# Something New Party Data

Party, election and candidate data for Something New, published in [Popolo](http://www.popoloproject.com) data format.

Published as Open Data under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## About the data

* `organizations` defines the party itself and its sub-organisations (the executive board and national officers). Uses the Popolo [Organization](http://www.popoloproject.com/specs/organization.html) model.
* `posts` defines a set of named posts within the different organisations. Uses the Popolo [Post](http://www.popoloproject.com/specs/post.html) model.
* `people` is a set of individuals referred to elsewhere. Uses the Popolo [Person](http://www.popoloproject.com/specs/person.html) model.
* `memberships` joins people to their posts within the different organisations. . Uses the Popolo [Membership](http://www.popoloproject.com/specs/membership.html) model.
* `elections` defines a set of events which are each specific elections. Each election (i.e. a general election) is an event, and individual wards or constituency elections within that are sub-events. Uses the Popolo [Event](http://www.popoloproject.com/specs/event.html) model.
* `candidacies` relates elections to candidates, using a membership relation. Popolo does not currently have a candidacy model (see [issue #104](https://github.com/popolo-project/popolo-spec/issues/104) on the spec repository), but this is a work in progress and not tightly defined.