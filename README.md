# Lost Lake Disc Club

Public pages for the game (privacy policy). Served with GitHub Pages:
https://coleocofer.github.io/lost-lake-disc-club/


`config.json` is the game's public ranking version policy. Both minimums remain zero
while friends test; this does not turn on the purchase paywall. After the required build
is available to players, set `min_build` to that build and `min_course_version` to its
`CourseHash.GENERATOR_VERSION`. Publish the file with every generator-changing release.
An unreachable or malformed endpoint leaves the game's last valid cached policy in place;
a player without a cached policy can still play. Offline Career is always available.
