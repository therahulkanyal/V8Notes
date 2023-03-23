 ## DECLARATION_NODE_LIST
    VariableDeclaration
    FunctionDeclaration

 ## ITERATION_NODE_LIST 
   DoWhileStatement          
   WhileStatement            
   ForStatement              
   ForInStatement            
   ForOfStatement

 ## BREAKABLE_NODE_LIST 
  Block                     
  SwitchStatement

 ## STATEMENT_NODE_LIST       
  ITERATION_NODE_LIST             
  BREAKABLE_NODE_LIST             
  ExpressionStatement             
  EmptyStatement                  
  SloppyBlockFunctionStatement    
  IfStatement                     
  ContinueStatement               
  BreakStatement                  
  ReturnStatement                 
  WithStatement                   
  TryCatchStatement               
  TryFinallyStatement             
  DebuggerStatement               
  InitializeClassMembersStatement 
  InitializeClassStaticElementsStatement

 ## LITERAL_NODE_LIST 
  RegExpLiteral           
  ObjectLiteral           
  ArrayLiteral

 ## EXPRESSION_NODE_LIST 
  LITERAL_NODE_LIST          
  Assignment                 
  Await                      
  BinaryOperation            
  NaryOperation              
  Call                       
  CallNew                    
  CallRuntime                
  ClassLiteral               
  CompareOperation           
  CompoundAssignment         
  Conditional                
  CountOperation             
  EmptyParentheses           
  FunctionLiteral            
  GetTemplateObject          
  ImportCallExpression       
  Literal                    
  NativeFunctionLiteral      
  OptionalChain              
  Property                   
  Spread                     
  SuperCallReference         
  SuperPropertyReference     
  TemplateLiteral            
  ThisExpression             
  Throw                      
  UnaryOperation             
  VariableProxy              
  Yield                      
  YieldStar

 ## FAILURE_NODE_LIST 
   FailureExpression