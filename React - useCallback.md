
# What is useCallback in React?
useCallback is a hook that will return a memoized version of the callback function that only changes if one of the dependencies has changed.

# What is the difference between useCallback and useMemo?
useCallback (callback, dependencies) can be used like useMemo(), but it memorizes functions instead of values, to prevent re-creation upon every render, which helps your application run faster.

useMemo is used when you don’t want to recompute the value that the function returns. It’s just that you cached the values returned from some function.

# Should we use useCallback everywhere?
No, instead you must consider whether using useCallback() is worth the performance increase compared to increased complexity.

# Why UseCallBack is used?
It is useful when passing callbacks to optimized child components that rely on reference equality to prevent unnecessary renders.

Simple, the usecallback hook is used when you have a component in which a child is rendering repeatedly without the need for it. Pass a callback and dependency array

# When not to useCallback?
When child component is light and its re-rendering doesn't create performance issues.
