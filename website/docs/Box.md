---
id: Box
title: Box
sidebar_label: Box
---
Basic Building block of all components. It can be used to contruct any component.
It is simmilar to a layer in Figma. It can have width, height, background color shadow etc. You can set these properties to create anything.



## How to use?

### Step 1 - Import 

```jsx 
import {Box} from '../uds' //Path to UDS folder
```

### Step 2 - Use component
```jsx 
<Box width="200px" height="50px" bg="neutral__200" p="2" >
        This is a box!
</Box>
```


## Live Playground
You can play with the code below to understand how this component works. You can apply any property to it listed in the section below.

export const Embed = ()=>(
    <embed
     src="https://codesandbox.io/embed/box-o9h16?autoresize=1&codemirror=1&fontsize=14&hidenavigation=1&module=%2Fsrc%2Fmain.js&theme=dark"
     style={{width:"100%", height: "500px"}}
   />
)

<Embed />





## Properties



### Width


| Description                    | value | Example|
|--------------------------------|-------|--------|
| Width as percentage of parent container | 0% - 100%  | ```<Box width="100%"></Box>```|
| Width as a specif pixel value | 200px | ```<Box width="200px"></Box>```|
| Width as a percentage value of the browser(view) width | 0vw - 100vw  | ```<Box width="100vw"></Box>```|

### Height

| Description                    | value | Example|
|--------------------------------|-------|--------|
| Height as percentage of parent container | 0% - 100%  | ```<Box height="100%"></Box>```|
| Height as a specif pixel value | 200px | ```<Box height="200px"></Box>```|
| Height as a percentage value of the browser(view) height | 0vh - 100vh  | ```<Box height="100vh"></Box>```|



### Spacings

#### Internal Spacing (padding)
0, 4, 8, 12, 16, 20, 24

| Description                    | value | Example|
|--------------------------------|-------|--------|
| All sides  | UDS Space Token  | ```<Box p="2"></Box>```|
| Top & Bottom  | UDS Space Token  | ```<Box py="2"></Box>```|
| Top  | UDS Space Token  | ```<Box pt="2"></Box>```|
| Bottom  | UDS Space Token  | ```<Box pb="2"></Box>```|
| Left & Right  | UDS Space Token  | ```<Box px="2"></Box>```|
| Left  | UDS Space Token | ```<Box pl="2"></Box>```|
| Right  | UDS Space Token  | ```<Box pr="2"></Box>```|

#### External Spacing (margin)
0, 4, 8, 12, 16, 20, 24

| Description                    | value | Example|
|--------------------------------|-------|--------|
| All sides  |UDS Space Token  | ```<Box m="2"></Box>```|
| Top & Bottom  | UDS Space Token  | ```<Box my="2"></Box>```|
| Top  | UDS Space Token  | ```<Box mt="2"></Box>```|
| Bottom  | UDS Space Token  | ```<Box mb="2"></Box>```|
| Left & Right  | UDS Space Token  | ```<Box mx="2"></Box>```|
| Left  | UDS Space Token  | ```<Box ml="2"></Box>```|
| Right  | UDS Space Token  | ```<Box mr="2"></Box>```|



### Colors


| Description                    | value | Example|
|--------------------------------|-------|--------|
| Background color| UDS Color Token  | ```<Box bg="neutral__200"></Box>```|
| Text color  | UDS Color Token|```<Box color="neutral__500"> I am neutral 500</Box>```|


## Sample Code






