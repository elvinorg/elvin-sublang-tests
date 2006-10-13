
A set of subscription tests
- names
- immediate values
  - int32
    - range
    - octal
    - hex
    - negative
  - int64
    - suffixes
    - range
    - octal
    - hex
    - negative
  - floats
    - simple
    - exponent
    - negative
    - negative exponent
    - ranges
  - strings
    - unicode
    - quoting
- functions
  - name
  - number of arguments
  - types of arguments
- arithmetic
- regex
- wildcard
- simplicity
- complexity


Tests are encoded in XML using the following format:

<test id="">
    <required-versions>
        <version number="4.0">Notes</version>
    </required-versions>
    <expression>require(a)</expression>
    <acceptable-results>
        <result code="0">Notes</result>
    </acceptable-results>
    <references>
        <section version="4.0" number="1.1">Notes</section>
    </references>
    <notes>
        Commentary here
    </notes>
</test>


