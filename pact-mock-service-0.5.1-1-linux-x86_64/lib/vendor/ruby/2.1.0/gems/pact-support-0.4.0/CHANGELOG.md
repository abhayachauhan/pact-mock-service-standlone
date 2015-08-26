Do this to generate your change history

  git log --pretty=format:'  * %h - %s (%an, %ad)'

### 0.4.0 (20 March 2015)

* 409bde5 - support url including basic authentication info, e.g.: http://username:password@packtbroker.com (lifei zhou, Wed Mar 18 21:49:29 2015 +1100)
* d0d42bb - added http basic authentication options when open uri (lifei zhou, Thu Feb 26 22:03:21 2015 +1100)

### 0.3.1 (24 Februrary 2015)

* e3d6d6d - Fixed bug when Content-Type is a Pact::Term. (Beth Skurrie, Tue Feb 24 17:25:10 2015 +1100)

### 0.3.0 (13 Februrary 2015)

* 4e29277 - Create a public API for extracting matching rules for pact-mock_service to use. (Beth Skurrie, Fri Feb 13 15:35:14 2015 +1100)
* 17ffb7e - Improve Pact::Term error message when value does not match regexp. (Beth Skurrie, Thu Feb 12 15:35:28 2015 +1100)
* ad0b37b - Added logic to convert Term and SomethingLike to v2 matching rules (Beth Skurrie, Thu Feb 12 14:55:34 2015 +1100)
* cc15c4d - Renamed <index not found> to <item not found>, and <index not to exist> to <item not to exist> (Beth Skurrie, Thu Feb 12 11:47:53 2015 +1100)
* 1b65c46 - Change "no difference here" to ... in unix diff output (Beth Skurrie, Thu Feb 12 11:43:58 2015 +1100)
* 3cb5b30 - Fix duplicate "no difference here!" in diff when actual array has more items than the expected (Beth Skurrie, Thu Feb 12 11:30:58 2015 +1100)
* a9da567 - Changed display of NoDiffAtIndex (Beth Skurrie, Tue Dec 23 15:16:49 2014 +1100)
* f9619e6 - Log warning message when unsupported rules are detected (Beth Skurrie, Tue Dec 23 14:42:22 2014 +1100)
* 9875bef - Added support for v2 regular expression matching in provider (Beth Skurrie, Tue Dec 23 14:15:00 2014 +1100)

### 0.2.1 (21 January 2015)

* 4e26c75 - Ignore HTTP method case when determining if routes match. https://github.com/bethesque/pact-support/issues/3 (Beth, Tue Jan 20 20:15:20 2015 +1100)
* af96eba - Allow request path to be a Pact::Term (Beth, Tue Jan 20 19:37:23 2015 +1100)

### 0.1.4 (20 January 2015)

A naughty release because bumping the minor version to 0.2.0 means I have to upgrade all the gems.

### 0.2.0 (20 January 2015)

* bb5d893 - Added option to UnixDiffFormatter to not show the explanation (Beth, Tue Jan 20 08:39:42 2015 +1100)

### 0.1.3 (12 December 2014)

* 27f3625 - Fixed bug rendering no diff indicator as JSON (Beth, Fri Dec 12 10:42:50 2014 +1100)

### 0.1.2 (22 October 2014)

* 00280ac - Added logic to match form data when specified as a Hash (bethesque, Wed Oct 22 15:21:39 2014 +1100)

### 0.1.1 (22 October 2014)

* ff6a01d - Disallowing unexpected params in the query (bethesque, Wed Oct 22 14:42:41 2014 +1100)

### 0.1.0 (22 October 2014)

* fa7e03f - Removed JSON serialisation code from models. It has been moved to decorators in pact_mock-service. (bethesque, Wed Oct 22 12:53:21 2014 +1100)

### 0.0.4 (20 October 2014)

* ebe5e32 - Added differ for application/x-www-form-urlencoded bodies. (bethesque, Mon Oct 20 20:26:13 2014 +1100)

### 0.0.3 (17 October 2014)

* bab0b34 - Added possibility to provide queries as Hash. Then order of parameters in the query is not longer relevant. (André Allavena, Tue Oct 14 00:24:38 2014 +1000)

### 0.0.2 (12 October 2014)

* e7080fe - Added a QueryString class in preparation for a QueryHash class (Beth, Sun Oct 12 14:32:15 2014 +1100)
* 8839151 - Added Travis config (Beth, Sun Oct 12 12:31:44 2014 +1100)
* 81ade54 - Removed CLI (Beth, Sun Oct 12 12:29:22 2014 +1100)
* 3bdde98 - Removing unused files (Beth, Sun Oct 12 12:11:48 2014 +1100)
* ef95717 - Made it build (Beth, Sat Oct 11 13:24:35 2014 +1100)
* 1e78b62 - Removed pact-test.rake (Beth, Sat Oct 11 13:20:49 2014 +1100)
* 3389b5e - Initial commit (Beth, Sat Oct 11 13:13:23 2014 +1100)
