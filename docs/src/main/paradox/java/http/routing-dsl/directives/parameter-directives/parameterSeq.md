<a id="parameterlist-java"></a>
# parameterList

## Description

Extracts all parameters at once in the original order as (name, value) tuples of type `Map.Entry<String, String>`.

This directive can be used if the exact order of parameters is important or if parameters can occur several times.

See @ref[When to use which parameter directive?](index.md#which-parameter-directive-java) to understand when to use which directive.

## Example

@@snip [ParameterDirectivesExamplesTest.java](../../../../../../../test/java/docs/http/javadsl/server/directives/ParameterDirectivesExamplesTest.java) { #parameterSeq }