This repository demonstrates a common issue with React Router v6's catch-all route ('*').  When used without careful consideration, the catch-all route can create an infinite render loop, resulting in the infamous 'too many re-renders' error. The solution involves correct route ordering and using `useLocation` or `useParams` hooks.