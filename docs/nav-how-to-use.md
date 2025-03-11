# **Navigation Package**

## **Overview**
- To use the navigation properly, three components are essential for the workflow:
    - **AI Navigation Package**: Use this to create the `Navmesh Surface`. Ensure you have the Navmesh Builder Script.
    - **Target Setup** : For setting up the target/destination gameobject.
    - **Navigator Script**: Utilize this script to create the navigation path.

!!! note "Get started with Navigation"
    To get started with navigation, we need to import the `Navigation Package` to your unity project.

## **Requirements**

To use the script, ensure the following prerequisites are met:

!!! danger "Navmesh Component"
    Without a **nav mesh**, the package won't work. Make sure you use the `navmesh builder` script to create a `navmesh surface` at runtime.

!!! info "Required Prefabs"
    1. Line Renderer Prefab
    2. Directional Arrow Prefab
    3. Smaller Arrow Prefab
    4. Corner Arrow Prefab
    5. Destination Prefab

## **Navmesh Setup for Runtime**

!!! info "If you want a `navmesh surface` at runtime, follow this part or skip to the next step."

- On your `Terrain` GameObject, add a `navmesh surface` component, then add the `navmesh builder` script.

## **Target Setup**

To set up the target/destination, follow these steps:

- Mark the target/destination GameObject with `Tag: Target`.
-  Add a `N**avMeshModifier` component to the GameObject and set it to **Remove**.

!!! info "Why?"
    This ensures that the GameObject is included on the NavMesh surface. By doing this, the GameObject will not be excluded when creating the NavMesh at runtime. **You can turn it off to see the results**.

## **Navigator Setup**
The navigator script has different compoents that we can change and customize dependin on how you want to se it up, some pre-built prefabs are insitialized 