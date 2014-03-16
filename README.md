#Lambda Activator

An Activator that uses lambda expression to create objects

## Usage

    LambdaActivator.CreateInstance<MyClass>();
    LambdaActivator.CreateInstance<MyClass>(param1, param2, param3);
    LambdaActviator.CreateInstance(Type.Get("MyClass"));
    LambdaActviator.CreateInstance(Type.Get("MyClass"), param1, param2, param3);
