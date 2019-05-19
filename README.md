# android-check-one-capital-lowercase-number
Android check string contains at least one capital letter, lowercase letter and number

<pre>
public final Pattern textPattern = Pattern.compile("^(?=.*[a-z])(?=.*[A-Z])(?=.*\\d).+$");
</pre>

Second you can use it like this:

<pre>
public boolean isTextValid(String textToCheck) {
return textPattern.matcher(textToCheck).matches();
}
</pre>
