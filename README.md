## Useful snippets

To add new incident you can add the following markup to the top :
```html
<div class="note">
  <h3 class="last-incident-date">Tuesday February 24, 2022</h3>
  <p>
    No issues reported, all Systems Operational.
  </p>
</div>
```

**List of icons for each state :**

No known issues:
```html
<span>
  <svg viewBox="0 0 20 20" fill="#007f5f" focusable="false" aria-hidden="true">
    <path
      d="M10 18c-4.411 0-8-3.589-8-8s3.589-8 8-8 8 3.589 8 8-3.589 8-8 8zm0-14c-3.309 0-6 2.691-6 6s2.691 6 6 6 6-2.691 6-6-2.691-6-6-6zm-1 9a.997.997 0 0 1-.707-.293l-2-2a1 1 0 1 1 1.414-1.414L9 10.586l3.293-3.293a1 1 0 1 1 1.414 1.414l-4 4A.996.996 0 0 1 9 13z">
    </path>
  </svg>
</span>
```

Maintenance : 
```html
<svg viewBox="0 0 20 20" fill="#b98900" focusable="false" aria-hidden="true">
  <path fill-rule="evenodd"
      d="M10 18c-4.411 0-8-3.589-8-8s3.589-8 8-8 8 3.589 8 8-3.589 8-8 8zm2.293-4.707a.997.997 0 0 1-.707-.293l-2.293-2.293A.997.997 0 0 1 9 10V6a1 1 0 1 1 2 0v3.586l2 2a.999.999 0 0 1-.707 1.707z">
  </path>
</svg>
```
Degraded : 
```html
<svg viewBox="0 0 20 20" fill="#b98900" focusable="false" aria-hidden="true">
  <path
    d="M10 18a8 8 0 1 1 0-16 8 8 0 0 1 0 16zM9 9a1 1 0 0 0 2 0V7a1 1 0 1 0-2 0v2zm0 4a1 1 0 1 0 2 0 1 1 0 0 0-2 0z">
  </path>
</svg>
```
  
Partial Outage:
```html
<svg viewBox="0 0 20 20" fill="#d72c0e" focusable="false" aria-hidden="true">
  <path fill-rule="evenodd" d="M9 11a1 1 0 1 0 2 0V9a1 1 0 1 0-2 0v2zm0 4a1 1 0 1 0 2 0 1 1 0 0 0-2 0zm8.895 1.549-7-14.04c-.339-.679-1.45-.679-1.79 0l-7 14.04A1.004 1.004 0 0 0 3 18h14a1 1 0 0 0 .895-1.451z">
  </path>
</svg>
```
Partial:
```html
<svg viewBox="0 0 20 20" fill="#d72c0e" focusable="false" aria-hidden="true">
  <path d="M15 10a1 1 0 0 1-1 1H6a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1zm-5-8a8 8 0 1 0 0 16 8 8 0 0 0 0-16z">
  </path>
</svg>
```
