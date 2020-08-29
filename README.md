# fast-Javascript-SHA1

I had a requirement for SHA1 in a project but all the examples were rediculously slow, so I decided to write a solution myself using pre-calculated routines to help speed up the actual hashing of strings, I can now spawn the s2SHA1 class once and use it multiple times within fractions of seconds

quick usage example

var $ = new s2SHA1();
console.log($.sha1('the quick brown fox jumped over the lazy dog'));
/* result: 3e4991b48bcb1bd9d3c4c14a1f24c415deaba466 */

console.log($.sha1('all bound for mu mu land'));
/* result: 54cbad8fc5d0455dae4aa57ba1b6896915579095 */
