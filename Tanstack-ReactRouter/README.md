- useQuery caches requests, configure the cache timeout with `staleTime` -> `NewEventsSection.jsx`
- Enable and disable `useQuery` requests depending on state -> `FindEventSection.jsx`
- `useMutation` to send POST requests, and **invalidate queries** and **redirect to a route** if `mutationFn` succeed (`onSuccess`) -> `NewEvent.jsx`
- Render a Modal conditionally, depending on DELETE `useMutation` state -> `EventDetails.jsx`
- Implement **optimistic updating** while editing events and **roll back** if the request fails -> `EditEvent.jsx` `useMutate` function
- Implement React Router **loader function** in `EditEvent.jsx`
- Replace `useMutation` for an **action function** of React Router in `EditEvent.jsx`