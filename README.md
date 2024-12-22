# React Native FlatList: Empty List Bug

This repository demonstrates a common bug in React Native where a FlatList component renders an empty list even when the data array is populated. The bug is caused by improper state management. The solution involves using the useEffect hook to ensure the data is properly loaded into the state before rendering.