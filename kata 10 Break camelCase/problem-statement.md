Break camelCase
Complete the solution so that the function will break up camel casing, using a space between words.

Example
"camelCasing" => "camel Casing"
"identifier" => "identifier"
"" => ""

const chai = require("chai");
const assert = chai.assert;

describe("Sample Tests", () => {
it("Should pass sample tests", () => {
assert.strictEqual(solution('camelCasing'), 'camel Casing', 'Unexpected result')
assert.strictEqual(solution('camelCasingTest'), 'camel Casing Test', 'Unexpected result')
});
});
