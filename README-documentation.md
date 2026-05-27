## Tips

1. **Read first, code later** - Understand the entire codebase before making changes
2. **Prioritize ruthlessly** - Fix the most critical issues first
3. **Test constantly** - Run tests after each change
4. **Document as you go** - Write notes about what you find
5. **Make surgical fixes** - Change only what's necessary


## Changes
### 1. Security Issues
- Are there any security vulnerabilities?
- Is user input handled safely?
- Are there any exposed secrets or sensitive data?

### 2. **Performance Issues**
- Are there unnecessary re-renders?
- Is state management optimal?
- Are expensive calculations memoized?

### 3. **Code Quality**
- Are React best practices followed?
- Is the code maintainable and readable?
- Are there proper error boundaries?

### 4. **Accessibility**
- Are there accessibility issues?
- Are proper ARIA labels used?

### 5. **Developer Experience**
- Is the code well-structured?
- Are there proper TypeScript types (if applicable)?
- Is error handling adequate?


## Changes
### 1. 

### 5. // Issue 5: Function yang tidak di-memoize, re-create setiap render
menambahkan useCallback untuk memo-izing function


### 6. UUID collision because of Date.now()
menambahkan crypto.randomUUID() untuk menghasilkan UUID yang unik


### 7. Error Handling
menambah try catch block untuk error handling

### 8. useMemo (Done)
menggunakan useMemo untuk memo-izing logic filtering