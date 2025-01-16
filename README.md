# React useEffect Infinite Loop Bug
This repository demonstrates a common React bug involving the `useEffect` hook and its dependency array.  The initial implementation causes an infinite render loop because the dependency array is missing the state variable that changes within the effect. The solution shows how to fix this by correctly specifying the dependencies.