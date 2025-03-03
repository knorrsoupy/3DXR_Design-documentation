## An example of C-Sharp Script
``` c title="gamecontroller.c" linenums="1" hl_lines="6-9"
using UnityEngine;
using System.Collections.Generic;

public class GameController : MonoBehaviour
{
    [Header("Sign Settings")]
    [SerializeField] private GameObject potholeSign;
    [SerializeField] private GameObject rampSign;
    [SerializeField] private GameObject stairCase;

}
```