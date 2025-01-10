# Data Types in TypeScript

`TypeScript provides several data types to work with. Here are the main types:`

## Primitive Types

1. **Boolean**

   ```typescript
   let isDone: boolean = false;
   ```

2. **Number**

   ```typescript
   let decimal: number = 6;
   let hex: number = 0xf00d;
   let binary: number = 0b1010;
   let octal: number = 0o744;
   ```

3. **String**

   ```typescript
   let color: string = "blue";
   color = "red";
   ```

4. **Array**

   ```typescript
   let list: number[] = [1, 2, 3];
   let list: Array<number> = [1, 2, 3];
   ```

5. **Tuple**

   ```typescript
   let x: [string, number];
   x = ["hello", 10];
   ```

6. **Enum**

   ```typescript
   enum Color {
     Red,
     Green,
     Blue,
   }
   let c: Color = Color.Green;
   ```

7. **Any**

   ```typescript
   let notSure: any = 4;
   notSure = "maybe a string instead";
   notSure = false;
   ```

8. **Void**

   ```typescript
   function warnUser(): void {
     console.log("This is my warning message");
   }
   ```

9. **Null and Undefined**

   ```typescript
   let u: undefined = undefined;
   let n: null = null;
   ```

10. **Never**

    ```typescript
    function error(message: string): never {
      throw new Error(message);
    }
    ```

11. **Object**
    ```typescript
    let obj: object = { name: "John", age: 30 };
    ```

These types help in building robust and type-safe applications in TypeScript.
