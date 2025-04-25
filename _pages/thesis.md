/* Base nav link styling */
nav a {
  color: #4a4a4a;
  text-decoration: none;
  padding: 0.5em 1em;
  font-weight: 500;
  transition: color 0.3s ease;
}

/* Hover effect */
nav a:hover {
  color: #1d3557;
}

/* Active link styling – clean underline and bold */
nav a[href="{{ page.url | relative_url }}"] {
  border-bottom: 2px solid #457b9d;
  font-weight: 600;
  color: #1d3557;
}
