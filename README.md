# Svelte loading skeleton

_Also want to make svelte components? use the [svelte-component-template](https://github.com/YogliB/svelte-component-template)!_

---

Customizable loading skeleton for Svelte


## Installing
```yarn add svelte-loading-skeleton```

## Usage
```html
<script>
  import { Skeleton } from 'svelte-loading-skeleton';
</script>

<!-- All properties below are default -->
<Skeleton 
  width="100%"
  height="25px" 
  borderRadius="4px" 
  baseColor="rgb(238, 238, 238)" 
  highlightColor="rgb(245, 245, 245)" 
  animationLength="1.2s" 
/>

<!-- Use default skeleton -->
<Skeleton />

<!-- For custom elements -->
<loading-skeleton
  width="100%"
  height="25px" 
  borderRadius="4px" 
  baseColor="rgb(238, 238, 238)" 
  highlightColor="rgb(245, 245, 245)" 
  animationLength="1.2s" 
/>
```