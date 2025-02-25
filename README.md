# OpenTheDoor

## Vue 명명 규칙
1. **폴더** | kebab-case
2. **컴포넌트** | PascalCase
3. **메소드** | camelCase
4. **Props**
   - 부모(Template) | kebab-case
   - 자식(Script) | camelCase
   ```
   <UserProfile user-name="John" />
   
   <script setup>
   defineProps<{ userName: string }>();
   </script>
   ```
5. **Emit Events** | kebab-case
6. **Composables** | camelCase
7. **CSS 클래스** | kebab-case
8. **환경변수** | 대문자

